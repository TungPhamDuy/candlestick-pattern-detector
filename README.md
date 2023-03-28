# candlestick-pattern-detector

### Ứng dụng phương pháp Phân tích kỹ thuật Đồ thị nến Nhật Bản vào dự đoán biến động giá cổ phiếu của các Công ty S&P500.

**_License: This is a personal project of Tung Pham in order to serve as the midterm project for the Programming Package for Finance 1 course taken at the University of Economics and Law (VNU-HCM)_** 

**1. Thông tin chung**

**Tên đề tài:** Ứng dụng phương pháp phân tích kỹ thuật Đồ thị nến Nhật Bản vào dự đoán biến động giá cổ phiếu của các Công ty S&P500.

**Ngôn ngữ lập trình:** Python

**Nền tảng lập trình:** Pycharm

**Các package (gói) được sử dụng:** TA-Lib, flask, yfinance, pandas, datetime, csv, os

**Các file nằm trong thư mục:**
  + app.py (file chính: chứa chương trình và thuật toán)
  + patterns.py (file dictionary hỗ trợ: liệt kê các mẫu hình đồ thị nến)
  + datasets (file folder: chứa dữ liệu tự động tải về thông số chứng khoán khi chạy chương trình, đã được cập nhật đến ngày gần nhất (28/11))
  + templates\index.html (chứa mã html hiển thị cho web front end)
  + venv (file folder: tổng hợp môi trường interpreter cho chương trình)
  + TA_Lib-0.4.24-cp39-cp39-win_amd64.whl (file wrapped package talib cho python 3.9._ và máy 64bit)
  + report paper.pdf (file văn bản báo cáo project)
  + README.txt (file giới thiệu và thông tin chung)

**2. Trình bày kết quả**

**Mô tả:** Ứng dụng cho phép người dung chọn mẫu hình mà mình muốn phân tích trong số các mẫu hình đồ thị nến Nhật Bản, quét và nhận dạng các mẫu hình đó xuất hiện trong tất cả chỉ số giá cổ phiếu của các công ty S&P500 trong thời gian ngày thứ N-1 và đưa ra kết quả dự đoán xu hướng trong ngày hiện tại (N).
