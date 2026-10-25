<div align="center">

<img src="assets/banner.svg" alt="GCS Drone Arena" width="100%"/>

<a href="https://huyhoa308.github.io/gcs-drone-arena/">
  <img src="https://readme-typing-svg.demolab.com?font=Chakra+Petch&weight=600&size=24&duration=3000&pause=800&color=5EF0FF&center=true&vCenter=true&width=600&lines=%F0%9F%9A%81+Bay+qua+%C4%91%E1%BB%93i%2C+r%E1%BB%ABng%2C+h%E1%BB%93;%F0%9F%93%A6+G%E1%BA%AFp+th%C3%B9ng+h%C3%A0ng;%F0%9F%8F%81+Mang+v%E1%BB%81+v%C3%B9ng+GIAO+H%C3%80NG;%E2%8F%B1%EF%B8%8F+3+ph%C3%BAt+%E2%80%94+ai+giao+nhi%E1%BB%81u+nh%E1%BA%A5t%3F" alt="Typing SVG"/>
</a>

<br/>

[![Chơi ngay](https://img.shields.io/badge/▶_CHƠI_NGAY-trên_trình_duyệt-5ef0ff?style=for-the-badge&labelColor=0b1026)](https://huyhoa308.github.io/gcs-drone-arena/)
![Three.js](https://img.shields.io/badge/Three.js-3D-black?style=for-the-badge&logo=threedotjs)
![Offline](https://img.shields.io/badge/Offline-100%25-4dff88?style=for-the-badge&labelColor=0b1026)
![Xbox](https://img.shields.io/badge/Xbox-Controller-107C10?style=for-the-badge&logo=xbox&logoColor=white)
![ESP32](https://img.shields.io/badge/ESP32-Web_Serial-E7352C?style=for-the-badge&logo=espressif&logoColor=white)

</div>

---

## 🎮 Giới thiệu

Trò chơi drone gắp hàng **3D chạy trên trình duyệt**, dành cho học sinh. Điều khiển drone bay qua đồi, rừng, hồ; gắp thùng hàng và mang về vùng **GIAO HÀNG**.

<table>
<tr>
<td align="center">⏱️<br/><b>3 phút</b><br/><sub>mỗi lượt chơi</sub></td>
<td align="center">📦<br/><b>Gắp &amp; giao</b><br/><sub>đếm số món đã gắp / đã giao</sub></td>
<td align="center">🏆<br/><b>Bảng xếp hạng</b><br/><sub>lưu ngay trên máy</sub></td>
<td align="center">🌬️<br/><b>Gió</b><br/><sub>Tắt / Nhẹ / Mạnh</sub></td>
</tr>
</table>

## 🚀 Chạy

> [!TIP]
> Mở `index.html` bằng **Chrome** hoặc **Edge** (nhấp đúp). File đã nhúng sẵn Three.js và font, **không cần Internet**, copy sang máy khác vẫn chạy.

Hoặc chơi trực tuyến tại **[huyhoa308.github.io/gcs-drone-arena](https://huyhoa308.github.io/gcs-drone-arena/)**.

## 🕹️ Điều khiển

| Bàn phím | Tay cầm Xbox | Chức năng |
|:---:|:---:|---|
| <kbd>W</kbd> / <kbd>S</kbd> | Cần trái ↕ | Lên / xuống |
| <kbd>A</kbd> / <kbd>D</kbd> | Cần trái ↔ | Xoay |
| <kbd>↑</kbd> <kbd>↓</kbd> <kbd>←</kbd> <kbd>→</kbd> | Cần phải | Bay tới, lùi, sang ngang |
| <kbd>Space</kbd> | 🅰️ | Gắp / thả |
| <kbd>C</kbd> | 🅨 | Đổi camera (bám đuôi / từ trên / FPV) |
| <kbd>Enter</kbd> | ☰ MENU | START / STOP |
| <kbd>X</kbd> | 🅧 | Tắt động cơ khẩn cấp |

<details>
<summary><b>🎮 Tay cầm Xbox &amp; ESP32</b></summary>

<br/>

- **Xbox** (USB/Bluetooth): tự nhận khi nhấn một nút bất kỳ.
- **ESP32**: kết nối qua nút **USB** (Web Serial, 115200 baud).

Board gửi lên:
```
JOY1: throttle=.. yaw=..  JOY2: roll=.. pitch=..
```
Game gửi ngược về board:
```
$SIMTEL,roll,pitch,yaw,m1,m2,m3,m4,armed,alt,spd
```

</details>

## ⚙️ Tùy chọn

- 🛬 **Hỗ trợ giữ độ cao** (bật mặc định): thả cần ga là drone đứng yên.
- 🌬️ **Gió**: Tắt / Nhẹ / Mạnh.

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:3a3f8f,100:0b1026&height=100&section=footer" width="100%"/>

<sub>Làm bằng ❤️ cho các phi công nhí · © Truong Huy Hoa</sub>

</div>
