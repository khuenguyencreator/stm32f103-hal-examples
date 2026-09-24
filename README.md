# STM32F103 HAL Examples

Code ví dụ lập trình **STM32F103C8T6 (Blue Pill)** bằng thư viện **HAL**, cấu hình với **STM32CubeMX** và build bằng **Keil MDK-ARM**. Mỗi thư mục tương ứng một bài trong series lập trình STM32 trên blog [khuenguyencreator.com](https://khuenguyencreator.com).

- MCU: STM32F103C8T6
- Cấu hình: STM32CubeMX (file `.ioc` trong mỗi project)
- IDE / Compiler: Keil µVision 5 (MDK-ARM)
- Nạp / debug: ST-Link

## Danh sách bài

| Bài | Nội dung |
|---|---|
| [Bai3_Blink_Led](Bai3_Blink_Led) | GPIO Output – nháy LED |
| [Bai4_EXTI](Bai4_EXTI) | Ngắt ngoài EXTI |
| [Bai5_Timer_Base](Bai5_Timer_Base) | Timer cơ bản, ngắt tràn timer |
| [Bai6_IC_OC_Tim2](Bai6_IC_OC_Tim2) | Input Capture / Output Compare với TIM2 |
| [Bai7_PWM](Bai7_PWM) | Băm xung PWM |
| [Bai8_ADC_Single_Cont](Bai8_ADC_Single_Cont) | ADC 1 kênh, chế độ Single / Continuous |
| [Bai9_ADC_Scan](Bai9_ADC_Scan) | ADC nhiều kênh, chế độ Scan |
| [Bai10_I2C_DS3231](Bai10_I2C_DS3231) | Giao tiếp I2C với RTC DS3231 |
| [Bai11_UART_IT_DMA](Bai11_UART_IT_DMA) | UART dùng ngắt và DMA |
| [Bai12_SPI_Echo](Bai12_SPI_Echo) | Giao tiếp SPI |
| [Bai13_RTC](Bai13_RTC) | RTC nội |
| [Bai14_IWDG](Bai14_IWDG) | Independent Watchdog |
| [Bai15_WWDG](Bai15_WWDG) | Window Watchdog |
| [Bai16_USB_CDC](Bai16_USB_CDC) | USB Device CDC (cổng COM ảo) |
| [Bai17_USB_HID](Bai17_USB_HID) | USB Device HID (chuột) |
| [Bai18_USB_HID_KEYBOARD](Bai18_USB_HID_KEYBOARD) | USB Device HID (bàn phím) |
| [Bai19_USB_HID_Custom](Bai19_USB_HID_Custom) | USB Custom HID |
| [Bai20_STM32_Flash](Bai20_STM32_Flash) | Đọc / ghi Flash nội |
| [Bai21_GPIO_Bit_Band](Bai21_GPIO_Bit_Band) | Truy cập GPIO bằng Bit-Banding |
| [Bai22_Retarget_Printf](Bai22_Retarget_Printf) | Retarget `printf` ra UART |
| [Bai22_STM32_CAN_BUS](Bai22_STM32_CAN_BUS) | Giao tiếp CAN Bus |

## Cách sử dụng

1. Tải repo:
   ```bash
   git clone https://github.com/khuenguyencreator/stm32f103-hal-examples.git
   ```
2. Mở file `MDK-ARM/*.uvprojx` trong thư mục bài muốn chạy bằng Keil µVision.
3. Build (F7), cắm ST-Link rồi nạp (F8).
4. Muốn thay đổi cấu hình chân / ngoại vi: mở file `.ioc` bằng STM32CubeMX, chỉnh rồi Generate Code lại.

## Liên kết

- 📖 Bài viết hướng dẫn chi tiết: [khuenguyencreator.com](https://khuenguyencreator.com)
- 📚 Các repo khác: [github.com/khuenguyencreator](https://github.com/khuenguyencreator)

Nếu thấy hữu ích, hãy bấm ⭐ **Star** để ủng hộ nhé! Có lỗi hoặc thắc mắc, bạn tạo **Issue** trong repo này hoặc để lại bình luận trên blog.
