# Xây dựng và đánh giá hiệu quả các mô hình học máy dựa trên cây quyết định với bài toán dự báo khách hàng ngừng tham gia tín dụng
Xem nhanh bài báo cáo: https://github.com/giahuy2610/Decision-trees-for-predicting-customer-churn/blob/main/Report_Data_Mining_2023.pdf

## Thành viên:
Trịnh Gia Huy - 20520556@gm.uit.edu.vn  
Phạm Lê Dịu Ái - 20520368@gm.uit.edu.vn  
Lương Nguyễn Thành Nhân - 20520667@gm.uit.edu.vn  
Nguyễn Thị Thảo Hồng - 20520192@gm.uit.edu.vn  

## Tóm tắt nội dung
Với sự phát triển không ngừng của Internet và hoạt động ngân hàng, ngày càng nhiều người sử dụng thẻ tín dụng – credit card, do đó việc giữ chân khách hàng nhằm duy trì tỉ suất lợi nhuận là rất quan trọng đối với nhiều ngân hàng khi mà việc cạnh tranh giữa các ngân hàng rất khốc liệt. Do đó, nhóm tác giả đề xuất sử dụng học máy vào việc dự đoán việc khách sẽ ngừng sử dụng tín dụng để hỗ trợ ngân hàng đưa ra quyết định hoặc có thể thay đổi chương trình, dịch vụ để phục vụ và giữ được lượng khách hàng trung thành.  
Với ưu điểm như dễ hiểu và dễ cấu hình, hiệu quả cao nên các thuật toán học máy dựa trên cây quyết định rất phù hợp cho bài toán trên. Bài nghiên cứu sử dụng 3 thuật toán ID3, Random Forest, XGBoost và đồng thời sử dụng 3 kĩ thuật Oversampling, Udersampling, SMOTE để xử lý mất cân bằng dữ liệu nhằm lập so sánh hiệu quả giữa các thuật toán đại diện cho 3 loại thuật toán, đơn giản - tổng hợp - tăng cường.  
Kết quả thực nghiệm cho thấy, dựa trên độ đo ROC-AUC, kết quả cho thấy thuật toán XGBoost có độ chính xác cao nhất với tỉ lệ khoảng 97% và kĩ thuật xử lý mất cân bằng dữ liệu Oversampling cho ra kết quả có độ chính xác cao hơn 2 kĩ thuật còn lại.  

## Kết quả
![image](https://github.com/giahuy2610/Decision-trees-for-predicting-customer-churn/assets/87313146/5ec7b532-9306-42e0-b705-97093ac41f7c)
![image](https://github.com/giahuy2610/Decision-trees-for-predicting-customer-churn/assets/87313146/96feda56-d27b-47b4-8930-dfef9e79be5b)
![image](https://github.com/giahuy2610/Decision-trees-for-predicting-customer-churn/assets/87313146/21be60d1-5533-449a-9486-72bf4120626d)



