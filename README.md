# Project: Sentiment Analysis - Phân tích cảm xúc khách hàng

## 1. Giới thiệu: 
-  **Sentiment Analysis** là nhóm các bài toán con thuộc vào phân loại văn bản. Với mục tiêu phân
 tích và đánh giá các bình luận của khách hàng cho các sản phẩm và tích cực, tiêu cực hay trung tính.

- Project này dùng bộ dữ liệu ***IMDB-Dataset - Đánh giá phim*** để giải quyết bài toán phân tích cảm xúc

## 2. Tiền xử lý (preprocessing), Data mining, Huấn luyện, đánh giá mô hình
- ***Tiền xử lý***
    - **Remove HTML tag**: xóa các thẻ HTML
    - **Remove icon**: Xóa các kí tự icon
    - **Remove url**: xóa url
    - **Lowercase**: chuyển tất cả message thành chữ thường
    - **Punctuation Removal**: xóa dấu câu
    - **Tokenize**: chuyển message thành token
    - **Remove Stopword**: xóa các từ không quan trọng (trong tiếng anh)
    - **lemmatize & Stemming**: chuyển các từ về dạng nguyên thể
    - ...
- ***Biểu diễn văn bản thành vector***: dùng kỹ thuật TF-IDF
- ***Huấn luyện mô hình***: 
    - Sử dụng các mô hình khác nhau như: *Decission Tree Classifier, Random Forest, AdaBoost, Gradient Boost, XGBoost* để huấn luyện và đánh giá mô hình