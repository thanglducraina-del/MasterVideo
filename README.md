# MasterVideo

**MasterVideo** là phần mềm Windows giúp làm video YouTube không lộ mặt (faceless) gần như tự động:
kịch bản → giọng đọc AI → ảnh / clip AI / cảnh 3D → hiệu ứng âm thanh, nhạc nền → dựng video có phụ đề → Shorts → gói đăng YouTube.
Có thêm chế độ **dựng video review sản phẩm** từ ảnh người review + ảnh sản phẩm + kịch bản.

*MasterVideo is a Windows app that builds faceless YouTube videos almost automatically:
script → AI voice-over → AI images / clips / 3D scenes → sound effects and music → edited video with captions → Shorts → YouTube upload pack.
It also builds product-review videos from reviewer photos, product photos and a script.*

🌐 **Trang giới thiệu / Website:** https://thanglducraina-del.github.io/MasterVideo/

## Tải về / Download

Vào mục **[Releases](../../releases/latest)** và tải file `MasterVideo_Setup_V….exe` mới nhất.
*Go to **[Releases](../../releases/latest)** and download the latest `MasterVideo_Setup_V….exe`.*

### Windows chặn bộ cài ("Smart App Control blocked an app")?

Windows 11 cài mới thường bật sẵn **Smart App Control**. Tính năng này chặn phần mềm chưa có chữ ký số, trong đó có bộ cài MasterVideo. Muốn cài, anh/chị tắt tính năng này:

1. Bấm phím Windows, gõ **Smart App Control**, chọn **Smart App Control settings**.
2. Chọn **Off**, rồi bấm **Yes** khi Windows hỏi.
3. Chạy lại bộ cài `MasterVideo_Setup_V1.0.10.exe`.

**Lưu ý quan trọng:** sau khi tắt, Windows KHÔNG cho bật lại Smart App Control, trừ khi cài lại Windows. Các lớp bảo vệ khác vẫn hoạt động bình thường: Microsoft Defender (diệt virus), tường lửa, SmartScreen. Chỉ tải bộ cài từ trang chính thức: https://github.com/thanglducraina-del/MasterVideo/releases

Nếu thấy màn hình xanh "Windows protected your PC" (SmartScreen), bấm **More info** rồi bấm **Run anyway**.

### Windows blocked the installer ("Smart App Control blocked an app")?

New Windows 11 installs often turn on **Smart App Control**, which blocks software that has no code signature, including the MasterVideo installer. To install:

1. Press the Windows key, type **Smart App Control**, open **Smart App Control settings**.
2. Choose **Off** and confirm with **Yes**.
3. Run `MasterVideo_Setup_V1.0.10.exe` again.

**Important:** once turned off, Smart App Control cannot be turned back on without reinstalling Windows. Your other protections keep working: Microsoft Defender antivirus, firewall, SmartScreen. Only download the installer from the official page: https://github.com/thanglducraina-del/MasterVideo/releases

If you see the blue "Windows protected your PC" screen (SmartScreen), click **More info** → **Run anyway**.

**Các bước cài / Install steps:**

1. Bấm đúp file cài. Windows có thể hiện **«Windows protected your PC»** (SmartScreen) vì bộ cài chưa có chữ ký số trả phí: bấm **More info → Run anyway**.
   *Windows SmartScreen may warn because the installer is not code-signed yet: click **More info → Run anyway**.*
2. Chọn **I accept the agreement**, giữ thư mục gợi ý (ổ D: hoặc E:), **Install**.
   *Accept the agreement, keep the suggested folder (drive D: or E:), Install.*
3. Mở **Master Video - Bang dieu khien** ngoài Desktop → thẻ **KIỂM TRA MÁY & TẢI MODEL** → **KIỂM TRA MÁY** và bấm nút tải ở mục còn thiếu.
   *Open the desktop shortcut → **MACHINE CHECK & MODEL DOWNLOAD** card → run the check and click the download buttons for missing items.*

## Dùng thử / Trial

- **Dùng thử miễn phí 7 ngày hoặc 3 video** (cái nào hết trước), không cần key. Mở mọi tính năng trừ *Tìm kiếm & phân tích ngách*. Dựng lại cùng kịch bản và cắt Shorts không tính thêm video.
  *Free trial: 7 days or 3 videos, whichever comes first, no key needed — everything except niche research. Re-rendering the same script and cutting Shorts do not count.*
- Hết dùng thử cần key gói ĐẦY ĐỦ: bảng điều khiển → **Bản quyền** → **Sao chép mã máy** → gửi mã máy để mua key (nút **☎ Liên hệ** trong phần mềm, hoặc email bên dưới). Video đã làm vẫn mở và đăng bình thường.
  *After the trial a full licence key is required: control panel → **Licence** → **Copy machine code**, then send it to buy a key (**☎ Contact** button in the app, or the email below). Videos you already made stay usable.*

## Cập nhật / Updates

Nút ở góc trên bên phải bảng điều khiển: **xanh** = đang dùng bản mới nhất, **đỏ** = có bản mới → bấm để tự cập nhật (phần mềm chờ xong video đang dựng rồi mới cài).
*Top-right button: **green** = up to date, **red** = new version available → click to update (it waits until the current render finishes).*

## Lưu ý / Notes

- **Dịch vụ trả phí dùng key của bạn (BYOK):** ElevenLabs, Google Gemini, fal.ai, Runway, Fish Audio, Azure… Bạn trả tiền trực tiếp cho nhà cung cấp. Không có key vẫn dùng được giọng miễn phí trên máy, ảnh/clip trên card NVIDIA, nhạc nền tự tạo.
  *Paid services use your own keys (BYOK); you pay providers directly. Without keys you can still use free on-device voices, local NVIDIA image/clip generation and generated background music.*
- **ComfyUI, FFmpeg và Blender không nằm trong bộ cài** — phần mềm tải bản chính thức về máy bạn khi bạn bấm nút.
  *ComfyUI, FFmpeg and Blender are not bundled — the app downloads the official releases to your PC when you ask it to.*
- Repo này chỉ chứa **bộ cài** và file thông tin cập nhật có chữ ký số; không chứa mã nguồn.
  *This repository only hosts the installer and the signed update file; it contains no source code.*
- Mỗi bộ cài kèm hướng dẫn tiếng Việt và tiếng Anh, chính sách quyền riêng tư và giấy phép phần mềm bên thứ ba.
  *Each installer includes Vietnamese and English guides, the privacy policy and third-party licences.*

## Liên hệ / Contact

**thanglducraina@icloud.com**
