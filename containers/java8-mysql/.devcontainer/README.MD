# **Java 8 và MySQL Containers**

Folder này chứa 2 container, Java 8 và MySQL bản mới nhất. 2 Container này được cấu hình để chạy bởi docker-compose. Mặc định, VSCode sẽ tự động tìm đến file docker-compose.yml và run các container này lên.

## **Configuration**

### **Port**

Java 8 Container được bind sẵn port `8080` sử dụng cho ứng dụng spring boot, để mở thêm port vui lòng xem tại mục `forwardPorts` trong file `devcontainer.json`

MySQL Container được bind sẵn port `3306` vui lòng xem tại file `.env` cho cấu hình port và Database

### **Biến môi trường**

Tùy từng dự án có các biến môi trường với tên khác nhau, vui lòng thay đổi tên hoặc thêm các biến môi trường mới ở mục `environment` trong file `docker-compose.yml`
