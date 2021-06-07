# GSI Builder
## Yêu cầu:
- Phải là ROM.zip
- ROM phải hỗ trợ treble
- Đừng thử OneUI
- Download link phải là direct link (link bấm vào là down file)

## Hướng dẫn:
1. Fork
2. Bấm vào tập tin workflow và sửa builder.yml
3. Sửa ROM's link
4. Star và xem ở Action
5. Download link sẽ có ở phần Up GSI lên GoFile

- Note: Nếu muốn build lại GSI hoặc build GSI khác, bạn cần đổi link, bấm unstar rồi bấm star

## Thông tin:
ROM_LINK: Link tải GSI

ROM_TYPE: Loại GSI, ví dụ:
1. Android 9: Generic, ColorOS, CubotOS, Flyme, Funtouch, JoyUI, MIUI, Moto, Nubia, OneUI, OxygenOS, Pixel, RazerUI, RogUI, VOS, Xperia, ZUI, ZenUI
2. Android 10: Generic, ColorOS, Flyme, JoyUI, LGUX, MIUI, Moto, OriginOS, OxygenOS, Pixel, RogUI, VOS, ZUI, ZenUI
3. Android 11: Generic, Pixel, VOS
4. Android 12 S: Generic, Pixel
- Note: Đừng đổi ROM_TYPE thành các loại linh tinh như Generic Bruh

BUILD_AB: sửa thành true để build Arm64 AB GSI

BUILD_AONLY: sửa thành true để build Arm64 A Only GSI

ROM_AB: Tên file Rom AB, bạn có thể đổi thành bất cứ thứ gì nhưng phải giữ .zip

ROM_AONLY: Tên file Rom A Only, bạn có thể đổi thành bất cứ thứ gì nhưng phải giữ .zip

## Ví dụ:

ROM_LINK: #direct link

ROM_TYPE: Generic

BUILD_AB: true

BUILD_AONLY: false

ROM_AONLY: Generic_Arm64_A_Only.zip

ROM_AB: Generic_Arm64_AB.zip

## Credit:
- Nguồn tool: toan704
- Nâng cấp và chỉnh sửa tool: ping2019
- Chỉnh sửa tool (2): TienDungVN

### Group hỗ trợ
Telegram: https://t.me/dunggvngroup
