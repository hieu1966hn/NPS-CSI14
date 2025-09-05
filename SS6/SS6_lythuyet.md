Buổi 6: Xử lý ngôn ngữ tự nhiên
- Kỹ thuật Tokenization: Một văn bản dài được chia nhỏ thành các đơn bị nhỏ hơn gọi là "token".
- Token có thể là: 
+ Từ (word-level tokenization)
+ Ký tự (character-level tokenization)
+ Cụm từ/ subword (subword-level tokenization - thường dùng trong mô hình hiện đại như: BERT, GPT)

=> Tokenization giúp máy tính "hiểu" văn bản bằng cách cắt nó thành những mảnh nhỏ dễ xử lý hơn.

MỘT VÀI VÍ DỤ: 

**"Tôi yêu lập trình"**               **"I love programming in Python!"**
1) word-level tokenization 
=> ["Tôi","yêu","lập","trình","."]

2) character-level tokenization
=> ["T","ô","i"," ", ...."h","."]

2) subword-level tokenization
=> ["Tôi", "Yêu", "lập_trình", "."] => ["I","love","program","ming","in","Py","thon","!"]