# Sensor context

- Rig: Camera gắn phía trước xe (front-facing), hướng nhìn ra đường. Hình ảnh có định hướng portrait (1080x1920), cho thấy camera được lắp thẳng đứng. Dựa trên góc nhìn rộng và vị trí vòng kính, có thể camera gắn trên kính chắn gió phía trước, hoặc trên nóc xe gần gương chiếu hậu.
- `ego_body`: Phần capô xe nhìn thấy ở phía dưới cùng của frame, từ khoảng y=1700 trở xuống trong khung hình 1920px. Đây là vùng tối ở đáy ảnh, bên ngoài vòng kính.
- Vòng kính (lens circle): Nằm ở trung tâm, chiếm toàn bộ chiều rộng (100%) và ~93.5% chiều cao của khung hình. Dựa trên thống kê từ 48 frames: tâm trung bình tại (cx≈536, cy≈976) với bán kính trung bình r≈811px. Vòng kính hơi lệch sang trái (so với tâm 540) và lệch xuống phía dưới (so với tâm 960), bao phủ toàn bộ vùng nội dung chính.
