# Giới thiệu Bayesian statistics

Trong vòng những năm gần đây, ta thấy ngày càng có nhiều ứng dụng dựa trên kỹ thuật *Machine Learning*, đặc biệt là trong lĩnh vực search engine, thương mại điện tử, quảng cáo, mạng xã hội, v,v,.. Những ứng dụng này tập trung vào độ chính xác trong dự đoán và cần lượng data lớn ( tính bằng tetrabyte). Thực tế đó là nền tảng của những ông Tech lớn như Google, Facebook,..

Tuy nhiên, đa số những ứng dụng này là *blackbox*, nghĩa là không thể diễn giải được. Ví dụ như model quảng cáo trúng đích, người quản lý không biết model hoạt động như thế nào, chỉ cần nó cho kết quả tốt là được.  
Một nhược điểm thứ 2 là những ứng dụng này cần rất nhiều data. Ví dụ như trong ứng dụng quảng cáo định hướng, họ cần hàng triệu người sử dụng để tạo ra model quảng cáo.  

Những giới hạn này làm cho việc tạo model khó hơn ở những lĩnh vực ít data hoặc chuyên sâu. Nó cũng có thể gây tác dụng phụ trong bối cảnh liên quan tới sinh mạng và luật pháp như y học hoặc bảo hiểm. Ở đây, model dự đoán với độ chính xác phải kèm theo độ tin cậy để ước lượng nguy cơ.  
Ví dụ: Chúng ta phải ước lượng được sự không chắc chắn khi đưa ra chẩn đoán có bệnh cho con người.

**Bayesian** là một phương pháp phân tích có thể vượt qua những nhược điểm này. Kỹ thuật bắt đầu với thiết lập niềm tin bản thân vào hệ thống cần model, sau đó kết hợp với data thu thập được để tạo ra model bị ràng buộc bởi niềm tin bản thân và data.  
Từ model đó, ta có thể dùng để dự đoán và kèm theo đó là một độ tin cậy được biểu diễn bằng phân phối.  
Phương pháp Bayesian hoạt động tốt khi có dữ liệu ít, kèm theo khái niệm độ tin cậy, và có thể diễn giải được.

**Probabilistic programming** là một dạng lập trình bậc cao, có ưu điểm che đậy các phép tính toán phức tạp trong phương pháp bayesian.