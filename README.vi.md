<div align="center">
<table width="100%">
  <tr>
    <td align="left" width="120">
      <img src="https://cdn.jsdelivr.net/gh/quyen2867/cutcut@main/assets/logo-dark.png" alt="Concat" width="100" />
    </td>
    <td align="">
      <h1>Concat</h1>
      <h3 style="margin-top: -10px;">Trình thay thế CapCut hoàn toàn miễn phí, mã nguồn mở, đa nền tảng.</h3>
    </td>
  </tr>
</table>

<img src="https://cdn.jsdelivr.net/gh/quyen2867/cutcut@main/assets/editor.png" alt="Trình chỉnh sửa Concat" width="100%" />

<table width="100%">
  <tr>
    <td align="center" width="33%">
      <a href="#sponsoring"><b>Logo của bạn ở đây</b></a><br />
      <sub><a href="#sponsoring">Tài trợ Concat</a> và tên, logo, liên kết của bạn sẽ hiện ở vị trí này</sub>
    </td>
    <td align="center" width="34%">
      <a href="#sponsoring"><b>Logo của bạn ở đây</b></a><br />
      <sub><a href="#sponsoring">Tài trợ Concat</a> và tên, logo, liên kết của bạn sẽ hiện ở vị trí này</sub>
    </td>
    <td align="center" width="33%">
      <a href="#sponsoring"><b>Logo của bạn ở đây</b></a><br />
      <sub><a href="#sponsoring">Tài trợ Concat</a> và tên, logo, liên kết của bạn sẽ hiện ở vị trí này</sub>
    </td>
  </tr>
  <tr>
    <td align="center" width="33%">
      <a href="#sponsoring"><b>Logo của bạn ở đây</b></a><br />
      <sub><a href="#sponsoring">Tài trợ Concat</a> và tên, logo, liên kết của bạn sẽ hiện ở vị trí này</sub>
    </td>
    <td align="center" width="34%">
      <a href="#sponsoring"><b>Logo của bạn ở đây</b></a><br />
      <sub><a href="#sponsoring">Tài trợ Concat</a> và tên, logo, liên kết của bạn sẽ hiện ở vị trí này</sub>
    </td>
    <td align="center" width="33%">
      <a href="#sponsoring"><b>Logo của bạn ở đây</b></a><br />
      <sub><a href="#sponsoring">Tài trợ Concat</a> và tên, logo, liên kết của bạn sẽ hiện ở vị trí này</sub>
    </td>
  </tr>
</table>

<p align="center">
  <a href="https://github.com/quyen2867/cutcut/releases"><img src="https://img.shields.io/github/downloads/quyen2867/cutcut/total?style=flat-square&logo=github&logoColor=F8F8F8&label=Downloads&labelColor=212123&color=b394ff" alt="Tổng lượt tải" /></a>
  <a href="https://github.com/quyen2867/cutcut/actions/workflows/ci.yml"><img src="https://img.shields.io/github/actions/workflow/status/quyen2867/cutcut/ci.yml?style=flat&logo=githubactions&logoColor=F8F8F8&label=Build&labelColor=000000" alt="Trạng thái Build" /></a>
  <a href="https://github.com/quyen2867/cutcut/releases"><img src="https://img.shields.io/badge/Version-0.2.4-b394ff?style=flat-square&logo=semver&logoColor=F8F8F8&labelColor=212123" alt="Concat Phiên bản 0.2.4" /></a>
  <a href="LICENSE"><img src="https://img.shields.io/badge/License-AGPL%20v3-b394ff?style=flat-square&logo=gnu&logoColor=F8F8F8&labelColor=212123" alt="Giấy phép: AGPL-3.0-or-later" /></a>
</p>


</div>

<p align="center">
  <a href="./README.md">English</a> | <b>Tiếng Việt</b>
</p>

## Giới thiệu

Concat là trình chỉnh sửa video miễn phí, mã nguồn mở, thay thế CapCut cho macOS, Windows, Linux và Android. Nó bao phủ đúng những việc mà mọi người hay mở CapCut để làm: phụ đề tự động, chuyển văn bản thành giọng nói, xóa phông nền, animation keyframe, hiệu ứng và tiêu đề, cắt ghép nhiều track, xuất 4K. Mà không kèm điều kiện nào: không watermark, không tài khoản, không gói thuê bao, không upload.

Mọi thứ chạy hoàn toàn trên máy bạn với engine Rust gốc và GPU compositor. Cài vào, thả footage vào, cắt thôi. Các model AI cho phụ đề, giọng đọc và tách nền chỉ cần tải một lần trong Settings, sau đó chạy offline. Video của bạn không bao giờ rời khỏi ổ cứng.

**Phù hợp cho:** TikTok, Reels và Shorts, video YouTube, tutorial và quay màn hình, cắt podcast, meme.

**Cho cả máy móc:** API JSON-RPC, gRPC và MCP, nên script và AI agent cũng có thể cắt video với nó.

## Điểm nổi bật

- 🚫 **Không watermark. Không tài khoản. Không paywall.** Vĩnh viễn.
- 🔒 **100% chạy trên máy.** Không upload gì cả. Chạy offline.
- 💬 **Phụ đề tự động.** Whisper chạy trên máy. Chọn kích cỡ model, nhận phụ đề có style ngay trên timeline.
- 🗣️ **Chuyển văn bản thành giọng nói + nhân bản giọng.** Giọng miễn phí chạy trên máy, hoặc clone bất kỳ giọng nào chỉ từ vài giây ghi âm.
- 🧍 **Xóa phông nền.** Tách người, tách vật thể, hoặc tự vẽ mask.
- 🎞️ **Keyframe.** Vị trí, tỉ lệ, xoay, độ trong suốt, âm lượng, thông số hiệu ứng. Có sẵn trình sửa đường cong.
- ✨ **170+ hiệu ứng, bộ lọc, chuyển cảnh và animation chữ.** Render bằng GPU, xem trực tiếp trên preview.
- ✂️ **Cắt nhanh.** Split, trim, ripple, merge, freeze frame, tốc độ. Có magnetic timeline nếu bạn muốn.
- 🎚️ **Đa track, đa timeline.** Nhiều bản cắt trong một project. Có blend mode, crop, lật hình.
- 📝 **Tiêu đề.** Font chữ, viền, bóng đổ, nền. Có preset để bắt đầu nhanh.
- 🎙️ **Lọc giọng một chạm.** Khử ồn, làm đẹp giọng, cân bằng độ lớn. Thêm giọng chipmunk, robot, điện thoại và nhiều hiệu ứng khác.
- 📤 **Xuất file.** H.264, HEVC, AV1. Tối đa 4K 60fps, màu 10-bit.
- 🦀 **Engine Rust gốc.** GPU compositor, proxy, giải mã phần cứng. Kéo timeline 4K mượt.
- 🤖 **Điều khiển bằng script.** API JSON-RPC, gRPC và MCP, kèm CLI. AI agent có thể cắt video với nó.
- 🖥️ **macOS, Windows, Linux, Android.** 14 ngôn ngữ. Cùng một app, cùng file project.

## Tải về

Có 2 cách:

1. **[Trang web chính](https://concatenate.pages.dev/#download)** sẽ đưa bạn đúng bản build cho máy của mình. Hãy bắt đầu từ đây.
2. **[GitHub Releases](https://github.com/quyen2867/cutcut/releases)** có đầy đủ build cho mọi nền tảng, kèm bộ cài, package và checksum. Dùng khi bạn muốn tự chọn.

Concat đang ở giai đoạn **beta**: dùng được rồi, nhưng vẫn còn góc cạnh. Thấy lỗi thì [báo ở đây](https://github.com/quyen2867/cutcut/issues).

**Nền tảng**

- ✅ **Windows** · x86_64
- ✅ **macOS** · Intel và Apple silicon. File binary chưa được ký, nếu macOS không cho mở thì chạy: `xattr -dr com.apple.quarantine /Applications/Concat.app`
- ✅ **Linux** · x86_64 và ARM. Có `.deb`, `.rpm`, `.AppImage` và gói Arch
- ✅ **Android** · điện thoại và máy tính bảng
- 🧪 **iOS / iPadOS** · iPhone và iPad, cài sideload

✅ Được hỗ trợ · 🚧 Đang phát triển · 🧪 Chờ kiểm tra

**Cấu hình yêu cầu**

Concat chạy mọi thứ trên máy bạn, nên phần cứng quyết định giới hạn. Cấu hình tối thiểu là để chạy được; cấu hình đề nghị là để edit 1080p mượt và export 4K + chạy phụ đề không phải chờ lâu.

| | Tối thiểu | Đề nghị |
|---|---|---|
| **CPU** | CPU 64-bit bất kỳ từ 2013 trở lên | 6 nhân trở lên |
| **GPU** | Không cần. Không có GPU thì cửa sổ và màn preview sẽ dùng CPU | GPU hỗ trợ Metal (macOS), DirectX 12 (Windows) hoặc Vulkan (Linux) |
| **RAM** | **4 GB** | **16 GB** cho timeline 4K và model phụ đề lớn |
| **Ổ cứng** | **500 MB** cho app và model phụ đề nhỏ nhất | **2 GB** cho mọi model tùy chọn, cộng chỗ cho project và file xuất |

Các model tùy chọn tải trong Settings lần đầu rồi sau đó không cần mạng nữa: phụ đề tự động 78 MB tới 488 MB tùy cỡ whisper bạn chọn, chuyển văn bản thành giọng 132 MB hoặc 349 MB, tách người 15 MB, tách vật 179 MB, và cọ tách nền 40 MB.

## Bắt đầu

Tải về, mở lên, thả footage vào, cắt. Không tài khoản, không setup.

**Báo lỗi:** mỗi lần chạy đều ghi log, trong Settings › About có nút mở log và nút copy thông tin máy. Đính kèm cả 2 vào một [issue](https://github.com/quyen2867/cutcut/issues) là báo cáo đã đủ thông tin. 10 lần chạy gần nhất được giữ lại, nên log hôm qua vẫn còn; không có gì tự gửi đi đâu cả.

## Đóng góp

> [!IMPORTANT]
> Cách đóng góp tốt nhất là tải một bản build ở trang [Releases](https://github.com/quyen2867/cutcut/releases) về dùng: tìm xem nó hỏng ở đâu, và góp ý chỗ nào làm tốt hơn được.
>
> Muốn viết code? File [CONTRIBUTING.md](./CONTRIBUTING.md) hướng dẫn setup, cấu trúc thư mục, các check phải chạy, và cách cấp phép đóng góp. Muốn điều khiển Concat từ script, service hay agent? Thư mục [docs/](./docs/README.md) là tài liệu dev cho Concat API với các giao thức JSON-RPC, gRPC và MCP. [Discussion này](https://github.com/quyen2867/cutcut/discussions/3) là nơi project được công bố.

## Người đóng góp

<a href="https://github.com/quyen2867/cutcut/graphs/contributors">
  <img alt="Người đóng góp" src="https://contrib.rocks/image?repo=quyen2867/cutcut">
</a>

## Lịch sử Star

<a href="https://www.star-history.com/?repos=quyen2867%2Fcutcut&type=date&releases=&legend=bottom-right">
 <picture>
   <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/chart?repos=quyen2867/cutcut&type=date&theme=dark&legend=bottom-right" />
   <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/chart?repos=quyen2867/cutcut&type=date&legend=bottom-right" />
   <img alt="Biểu đồ lịch sử Star" src="https://api.star-history.com/chart?repos=quyen2867/cutcut&type=date&legend=bottom-right" />
 </picture>
</a>
