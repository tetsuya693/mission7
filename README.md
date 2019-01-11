撰寫一個Flask Server，設計一個端口為user，用戶能對此端口用GET方法訪問，並且挾帶query string，id=xxx。
若用戶傳入id=123，則傳回json {"userId":123}