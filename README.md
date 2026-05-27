# Dimension Invader

Một game thẻ bài chiến thuật lượt-luân-phiên cho Windows. Người chơi đối đầu với AI (hoặc người chơi khác) bằng minion và spell, mục tiêu phá hủy 3 lớp defense của đối thủ.

## Tải về & chơi

1. Vào tab **[Releases](../../releases)** ở trên (cạnh "Code")
2. Tải file `DimensionInvader-windows-vX.Y.zip` ở release mới nhất
3. Giải nén ra thư mục bất kỳ
4. Double-click `DimensionInvaderUnity.exe`

> **Lưu ý**: Windows có thể cảnh báo "Windows protected your PC" (SmartScreen) vì .exe chưa ký số — bấm **More info → Run anyway**. Game không yêu cầu cài đặt, không sửa registry, không cần admin.

### Yêu cầu hệ thống

- Windows 10/11 (64-bit)
- ~150 MB ổ cứng
- GPU hỗ trợ DirectX 11 trở lên (gần như mọi máy 2015+)
- Resolution khuyến nghị: 1920×1080 trở lên

## Cách chơi

### Mục tiêu
Phá hủy toàn bộ 3 defense (Lv1 → Lv2 → Lv3) của đối thủ, hoặc làm đối thủ hết deck.

### Thẻ bài
- **Minion**: triệu hồi lên field (tối đa 3 ô) để tấn công.
- **Spell**: dùng 1 lần, gây hiệu ứng tức thì (sát thương, hồi máu, draw...).
- **Defense**: 3 lớp tường, lớp ngoài cùng (Lv1) lộ mặt từ đầu, lớp khác lộ khi lớp ngoài bị phá.

### Lượt chơi
1. **Draw Phase**: +1 cost (max 10), rút 1 lá (turn 1 không rút).
2. **Main Phase**: chơi minion / cast spell.
3. **Attack Phase**: minion chưa rested có thể tấn công minion địch hoặc defense (turn 1 không tấn công).

### Mẹo
- Tay không có giới hạn → cứ tích lá chờ cost đủ.
- Click **void zone** xem các lá đã bỏ.
- Cast **Resurrect** → chọn minion từ void để hồi sinh.
- AI Easy/Intermediate/Hard có hành vi khác nhau — Hard ưu tiên spell mạnh và target minion yếu nhất.

## Modes

| Mode | Mô tả |
|---|---|
| **vs AI** | Chọn difficulty + deck của bạn + deck AI (preset theo difficulty hoặc deck bạn tự build) |
| **Player vs Player** | 2 người chơi luân phiên trên cùng máy (multiplayer online sẽ ra sau) |
| **Deck Builder** | Tạo và lưu deck riêng — không giới hạn số lá |

## Bản quyền & disclosure

Game được tạo cho mục đích học/giải trí cá nhân. Source code **không công khai**.

Built với Unity 6 (6000.4.8f1).

## Changelog

Xem tab **Releases** để biết các bản đã phát hành.
