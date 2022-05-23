# INT2215_1_SDL_Game
1.Cách cài đặt: 

🌟 Dùng thư viện SDL,SDL_image,SDL_ttf,SDL_mixer.

🌟Sử dụng đối tượng bảng gồm các đối tượng ô chiếu lên màn hình.

🌟Dùng BFS để đi từ nguồn theo các hướng của các ảnh sang các ô khác và dùng mảng check để đánh dấu, nếu đánh dấu hết các ô thì thắng.

🌟Chạy trên Visual Studio. 

2.Mô tả chung: Xoay ống nước để từ nguồn có thể đến được mọi ô khác, đối tượng bảng gồm các ô, mỗi ô có các giá trị tương ứng với các loại ô, khi xoay hoặc thay đổi trạng thái đánh dấu bằng BFS từ nguồn các ô thay đổi giá trị dẫn đến thay đổi loại ô.
Đồng thời game có hai chức năng game 4x4 và 5x5, mỗi chức năng random trong 3 ván từ file input, mỗi ván có nguồn ở vị trí giống nhau nhưng các loại ô ở các vị trí thì bị thay đổi.

3.Chức năng đã cài đặt: 

🌟Ghi điểm cao và lấy điểm cao từ file text.

🌟chèn âm thanh vào mỗi lần click vào ô, thêm thời gian, điểm số vào game.

🌟Sử dụng thuật toán BFS từ nguồn theo các hướng của ảnh để thăm các ô đi được, game có hai chức năng game 4x4 và 5x5, mỗi chức năng random trong 3 ván từ file input, mỗi ván có nguồn ở vị trí giống nhau nhưng các loại ô ở các vị trí thì bị thay đổi.

Link Youtube: https://youtu.be/7r64yKli0Ws

4.Các kỹ thuật lập trình: Sử dụng BFS, mảng tên các file input, ảnh, các lớp ô, bảng, dùng các hàm chung, dùng đồ họa SDL,SDL_image,SDL_ttf,SDL_mixer

5.Kết luận: Sử dụng đồ họa SDL và thuật toán BFS;
Hướng phát triển: Thêm nhiều ván vào mỗi chế độ hơn.
