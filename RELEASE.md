# Version 1.29

> Chúng tôi luôn cố gắng lắng nghe để cải thiện sản phẩm, sao cho việc phát triển ứng dụng thuận tiện hơn, nhanh hơn và cũng như chất lượng hơn.

## Tính năng mới

### Thêm Biometrics

- Biometrics hay còn gọi là xác thực sinh trắc học, là tính năng của thiết bị dùng để bảo mật quyền riêng tư bao gồm vân tay (TouchID), nhận diện gương mặt (FaceID), nhận diện móng mắt (Iris Recognition)...

- Chi tiết: <https://developers.tiki.vn/docs/api/device/bio-metrics/introduction>

## Sửa lỗi

- Hiển thị sai thông báo cho project sử dụng typescript

---

# Version 1.28

> Chúng tôi luôn cố gắng lắng nghe để cải thiện sản phẩm, sao cho việc phát triển ứng dụng thuận tiện hơn, nhanh hơn và cũng như chất lượng hơn.

## Cập nhật

- Tối ưu một số thành phần để giảm kích thước ứng dụng

- Tối ưu quá trình compile Tini App để tăng tốc ứng dụng

## Tính năng mới

- Hỗ trợ Typescript

  - Studio đã hỗ trợ xây dựng Tini App bằng Typescript: Bao gồm editor và compiler.

  - Chi tiết: <https://developers.tiki.vn/docs/development/studio/typescript-support>

- Tính năng Feedback

  - Trên thanh điều khiển của Studio, bạn có thể gửi đánh giá và phản hồi cho chúng tôi bằng cách nhấn vào nút Feedback.

---

# Studio 1.27

Chúng tôi luôn cố gắng lắng nghe để cải thiện sản phẩm, sao cho việc phát triển ứng dụng thuận tiện hơn, nhanh hơn và cũng như chất lượng hơn.

## Thay đổi có thể gây ảnh hưởng

### Mặc định sử dụng kiến trúc mới cho custom component

Như đã thông báo trước đó, những thay đổi bao gồm: Đồng bộ lifecycle giữa render và worker, tách biệt lifecycle methods và component methods. Những thay đổi sẽ được thông báo trong mục Console của DevTools.

Chi tiết: <https://community.tiki.vn/t/thong-bao-thay-d-i-v-ki-n-truc-ben-trong-c-a-custom-component/1852>

## Cập nhật

### Cập nhật dữ liệu trực tiếp trên App Data của DevTools

### Chỉnh sửa lại giao diện đăng nhập

## Tính năng mới

### Tính năng Clear All User Data

Cho phép xoá toàn bộ dữ liệu người dùng của Tini App Studio. Nhằm khắc phục các lỗi tiềm ẩn. Trong việc xoá dữ liệu người dùng, Tini App Studio sẽ tự động xoá dữ liệu đăng nhập nên bạn cần phải đăng nhập lại.

### Thêm navigator component

Navigator là component hỗ trợ điều hướng (routing) một cách trực tiếp trong txml.

Chi tiết: <https://developers.tiki.vn/docs/component/basic/navigation/navigator>

## Sửa lỗi

### Sửa lỗi onPageScroll

### Sửa lỗi css cho action sheet

---

# Studio 1.26

Chúng tôi luôn cố gắng lắng nghe để cải thiện sản phẩm, sao cho việc phát triển ứng dụng thuận tiện hơn, nhanh hơn và cũng như chất lượng hơn.

## Cập nhật

### Thêm currentTime cho onTimeUpdate trong video component

### Thêm event buffer cho video component

## Tính năng mới

### Tính năng App Data trong DevTools

App Data là một tính năng mới trong DevTools, mà bạn có thể xem các dữ liệu của từng màn hình ứng dụng.

## Sửa lỗi

### Sửa lỗi hiển thị sai giao diện của toolbar trên windows

### Sửa lỗi auto height của textarea component

---

# Studio 1.25

Chúng tôi luôn cố gắng lắng nghe để cải thiện sản phẩm, sao cho việc phát triển ứng dụng thuận tiện hơn, nhanh hơn và cũng như chất lượng hơn.

## Tính năng mới

### Thêm API my.getCart

my.getCart là API trả về tổng sản phẩm đang có trong giỏ hàng (cart) của Tiki.

Chi tiết: <https://developers.tiki.vn/docs/api/open/get-cart>

### Thêm API my.chooseVideo

my.chooseVideo là API dùng để quay video hoặc chọn video từ album cục bộ.

### Thêm API my.checkNativePermissions

my.checkNativePermissions là API dùng để kiểm tra người dùng đã bật các quyền cho Tiki app hay chưa.

Chi tiết: <https://developers.tiki.vn/docs/api/device/check-native-permissions>

## Sửa lỗi

### Sửa lỗi API my.getAllContacts cho iOS

### Sửa lỗi cập nhật giao diện transparent cho navigation bar

---

# Studio 1.24

Chúng tôi luôn cố gắng lắng nghe để cải thiện sản phẩm, sao cho việc phát triển ứng dụng thuận tiện hơn, nhanh hơn và cũng như chất lượng hơn.

## Tính năng mới

### Tính năng Breadcrumbs

Hiển thị vị trí hiện tại của file, cho phép di chuyển nhanh tới folders, files và symbols

### Lite mode ver 1.0 cho simulator

Hỗ trợ tính năng tách simulator ra một cửa sổ riêng nhằm tối ưu không gian code, di chuyển simulator sang các màn hình khác

## Thay đổi

### Xoá right arrow icon cho Address item

### Tự động thêm itm url cho các APIs: my.openScreen, my.openDeepLink

## Sửa lỗi

### Sửa lỗi kiểm tra trang thái đã check cho Checkbox

### Sửa lỗi đếm số kí tự cho Textarea

### Sửa lỗi tìm kiếm cho Input trên iOS

### Sửa lỗi chọn camera

---

# Studio 1.23

## Tính năng mới

### Thêm API my.loadFontFace

my.getAppSecret là API để load 1 web font.

Chi tiết: <https://developers.tiki.vn/docs/api/ui/font/load-font-face>

### Thêm API my.getAppIdSync

my.getAppIdSync là API dùng để lấy ID của Mini App hiện tại.

Chi tiết: <https://developers.tiki.vn/docs/api/basic/get-app-id>

### Thêm API my.onAcceleronmeterChange

my.onAcceleronmeterChange là một API để theo dõi các sự kiện thay đổi dữ liệu cảm biến gia tốc. Sau khi giao diện được gọi, quá trình giám sát sẽ tự động bắt đầu và khoảng thời gian gọi lại là 500ms. Bạn có thể sử dụng my.offAcceleronmeterChange() để dừng việc giám sát.

Chi tiết: <https://developers.tiki.vn/docs/api/device/acceleronmeter/on-acceleronmeter>

### Thêm API my.offAcceleronmeterChange

my.offAcceleronmeterChange là API giúp dừng việc theo dõi dữ liệu acceleronmeter.

Chi tiết: <https://developers.tiki.vn/docs/api/device/acceleronmeter/off-acceleronmeter>

### Thêm API my.offUserCaptureScreen

my.offUserCaptureScreen là API giúp dừng việc lắng nghe các sự kiện chụp màn hình.

Chi tiết: <https://developers.tiki.vn/docs/api/device//user-screenshot-event/off-user-capture-screen>

---

# Studio 1.22

## Cập nhật

### Thêm thuộc tính paymentMethod cho API my.makePayment

Thêm tham số paymentMethod: 'cod' nếu khách hàng chọn thanh toán tiền mặt khi giao hàng.

Chi tiết: <https://developers.tiki.vn/docs/api/open/make-payment>

## Tính năng mới

### Tính năng Code Completion cho Javascript

Tự động gợi ý syntax cho Javascript; hỗ trợ nhảy files, types, ...

### Giao diện mới cho tính năng tạo một project

Giao diện mới cho tính năng tạo một project. Hỗ trợ thêm tuỳ chọn tạo/không tạo folder mới, tạo/không tạo git repo.

### Hỗ trợ bật/tắt hot reload của simulator

Cho phép bật/tắt tính năng hot reload simulator mỗi khi lưu file. Nhằm mục đích để cho người dùng chủ động reload lại simulator khi cần thiết, cải thiện hiệu suất.

### Thêm API my.getAppSecret

my.getAppSecret là API dùng để lấy thông tin secret của Tini App hiện tại.

Chi tiết: <https://developers.tiki.vn/docs/api/basic/get-app-secret>

## Thêm API my.openAppSetting

my.openAppSetting là API dùng để mở app cài đặt của hệ thống và hiển thị màn hình các cài đặt tuỳ biến của app hiện tại (nếu có).

Chi tiết: <https://developers.tiki.vn/docs/api/device/open-app-setting>

### Thêm API my.pageScrollTo

my.pageScrollTo là API dùng để scroll đến vị trí bất kỳ trong trang.

Chi tiết: <https://developers.tiki.vn/docs/api/ui/page-scroll-to/page-scroll-to#sample-code>

### Thêm player component

Player component hỗ trợ xem video trên youtube, không giống như trên video component là hỗ trợ cho cả native và web video, player component chỉ hỗ trợ dạng web video.

Chi tiết: <https://developers.tiki.vn/docs/component/basic/media/player>

## Sửa lỗi

### Sửa lỗi AppLog panel không hoạt động

### Sửa lỗi Ad Banner không hiển thị trong webview

### Sửa lỗi overlay của date picker

---

# Studio 1.21

Chúng tôi luôn cố gắng cải thiện sản phẩm làm sao để việc phát triển ứng dụng thuận tiện hơn, nhanh hơn và cũng như chất lượng hơn. Tuy nhiên sẽ có những thay đổi phục vụ cho mục tiêu đó mà có thể dẫn tới việc không tương thích cho những ứng dụng Tini App hiện tại. Ở trong các phiên bản framework sắp tới, chúng tôi xin thông báo tới các developers về một số thay đổi có thể ảnh hưởng tới ứng dụng của bạn trên Tiki.

## Thay đổi có thể gây ảnh hưởng

### Kiến trúc mới cho custom component

Những thay đổi bao gồm: Đồng bộ lifecycle giữa render và worker, tách biệt lifecycle methods và component methods. Những thay đổi sẽ được thông báo trong mục Console của DevTools.

Chi tiết: <https://community.tiki.vn/t/thong-bao-thay-d-i-v-ki-n-truc-ben-trong-c-a-custom-component/1852>

## Cập nhật

### Cải thiện hiệu suất cho modal

Trong phiên bản mới, hiệu suất chuyển cảnh của các modal: toast, alert, prompt đã được tối ưu hóa.

### Cập nhật my.chooseVideo thêm giá trị để trả về original video

Trong phiên bản mới, API my.chooseVideo có thêm tuỳ chọn compressed để trả về original video.

Chi tiết: <https://developers.tiki.vn/docs/api/media/video/choose-video>

## Tính năng mới

### Thêm API my.makePayment

API dùng để tạo payment. Developer dùng api của Tiki để tạo order từ đơn hàng, sau đó gọi API my.makePayment để tạo khởi tạo, Tini App sẽ được redirect tới luồng payment của Tiki. Sau khi thanh toán thành công sẽ trả về callback success hoặc fail.

Chi tiết: <https://developers.tiki.vn/docs/api/open/make-payment>

### Thêm API my.addPhoneContact

API dùng để chọn ghi thông tin liên hệ vào sổ địa chỉ của điện thoại dưới dạng tạo một liên hệ mới hoặc thêm vào một liên hệ hiện có.

Chi tiết: <https://developers.tiki.vn/docs/api/device/add-phone-contact>

### Thêm API my.watchShake

API dùng để nhận sự kiện lắc thiết bị. Success callback chỉ được gọi một lần khi thiết bị được lắc sau khi API đã được gọi. Cần gọi lại API này nếu muốn nhận sự kiện thiết bị lắc ở lần sau.

Chi tiết: <https://developers.tiki.vn/docs/api/device/watch-shake>

## Sửa lỗi

### Sửa lỗi Studio không gợi ý syntax cho TCSS

### Sửa lỗi Tini App đôi khi không hoạt động trên iOS 12

---

# Studio 1.20

## Tính năng mới

### Thêm tính năng tự động gợi ý các thuộc tính cấu hình App, Page, Component

Trong phiên bản mới, Tini App Studio sẽ gợi ý các thuộc tính cấu hình và giá trị cho các thành phần của App, Page, Component trong json file.

### Thêm API my.getSetting

API lấy thông tin cài đặt. Trả về kết quả cài đặt quyền của người dùng. Chỉ quyền đã yêu cầu từ người dùng mới xuất hiện trong kết quả trả về.

Chi tiết: <https://developers.tiki.vn/docs/api/device/get-setting>

### Thêm API my.startCompass

API dùng để start theo dõi dữ liệu compass.

Chi tiết: <https://developer.tiki.vn/docs/api/device/compass/start-compass>

### Thêm API my.stopCompass

API dùng để dừng theo dõi dữ liệu compass.

Chi tiết: <https://developer.tiki.vn/docs/api/device/compass/stop-compass>

### Thêm API my.onCompassChange

API để theo dõi các sự kiện thay đổi dữ liệu compass. Sau khi giao diện được gọi, quá trình giám sát sẽ tự động bắt đầu và khoảng thời gian gọi lại là 200ms. Bạn có thể sử dụng my.offCompassChange() để dừng việc giám sát.

Chi tiết: <https://developer.tiki.vn/docs/api/device/compass/on-compass>

### Thêm API my.offCompassChange

API giúp dừng việc theo dõi dữ liệu compass.

Chi tiết: <https://developer.tiki.vn/docs/api/device/compass/off-compass>

### Thêm API my.onNetworkStatusChange

API dùng để nhận sự kiện thay đổi trạng thái mạng của thiết bị.

Chi tiết: <https://developer.tiki.vn/docs/api/device/on-network-status-change>

### Thêm API my.offNetworkStatusChange

API dùng để huỷ nhận sự kiện thay đổi trạng thái mạng của thiết bị.

Chi tiết: <https://developer.tiki.vn/docs/api/device/off-network-status-change>

## Sửa lỗi

### Sửa lỗi sai defaultTitle trong TabBar

### Sửa lỗi readonly color trong input

---

# Studio 1.19

## Tính năng mới

### Thêm tính năng tạo page, component

Trong phiên bản mới, bạn có thể tạo page, component bằng cách nhấn vào menu File chọn New Page hoặc New Component.

### Thêm API my.multiLevelSelect

API dùng để tạo component select đa cấp.

Chi tiết: <https://developers.tiki.vn/docs/api/ui/multi-level-select/multi-level-select>

### Thêm API my.optionsSelect

API dùng để tạo component Select. Bạn có thể tạo component Select 1 cấp hoặc 2 cấp.

Chi tiết: <https://developers.tiki.vn/docs/api/ui/option-selector/option-selector#giới-thiệu>

### Thêm API my.trimVideo

API cho phép cắt video trong 1 khoảng thời gian.

Chi tiết: <https://developers.tiki.vn/docs/api/media/video/trim-video>

### Thêm API my.vibrate

API dùng để làm rung thiết bị, với thời gian rung 200ms.

Chi tiết: <https://developers.tiki.vn/docs/api/device/vibrate>

### Thêm API my.vibrateShort

API dùng để làm rung thiết bị, với thời gian rung 40ms.

Chi tiết: <https://developers.tiki.vn/docs/api/device/vibrateShort>

### Thêm API my.vibrateLong

API dùng để làm rung thiết bị, với thời gian rung 400ms.

Chi tiết: <https://developers.tiki.vn/docs/api/device/vibrateLong>

### Thêm API my.openSetting

API dùng để mở cài đặt của thiết bị.

### Thêm API my.getNetworkType

API dùng để lấy thông tin kết nối mạng của thiết bị.

Chi tiết: <https://developers.tiki.vn/docs/api/device/get-network-type>

### Thêm API my.setKeepScreenOn

API dùng để giữ màn hình luôn sáng.

Chi tiết: <https://developers.tiki.vn/docs/api/device/keep-screen-on>

### Thêm API my.getScreenBrightness

API dùng để lấy thông tin độ sáng màn hình.

Chi tiết: <https://developers.tiki.vn/docs/api/device/get-screen-brightness>

### Thêm API my.callSecuritySystem

API này dùng để xác thực người dùng khi gọi các APIs lấy dữ liệu từ hệ thống Tiki.

### Thêm API my.exitMiniapp

API này cho phép các nhà phát triển thoát khỏi Tini App.

### Thêm API my.getBatteryInfo

API dùng để lấy thông tin pin của thiết bị.

Chi tiết: <https://developers.tiki.vn/docs/api/device/get-battery-info>

### Thêm API my.datePicker

API này cho phép các nhà phát triển tạo ra các hộp chọn ngày và giờ.

### Thêm cấu hình rootFontSize cho window và page

Trong phiên bản mới, chúng tôi thêm cấu hình rootFontSize cho window và page. Để thay đổi kích thước của font chính, bạn có thể thay đổi cấu hình này trong file `app.json` hoặc `.json` cho page của bạn.

## Sửa lỗi

### Sửa lỗi common command cho Studio: Select All, Copy, Paste, Cut, Delete

### Sửa lỗi decode không hoạt động trên text component

---

# Studio 1.18

## Hỗ trợ thêm API my.redirectTo

Trong phiên bản mới, chúng tôi hỗ trợ thêm API `my.redirectTo`.

API này cho phép các nhà phát triển có thể thay thế trang hiện tại bằng một trang khác.

Chi tiết có thể xem tại

<https://developers.tiki.vn/docs/api/ui/route/redirect-to>

## Hỗ trợ thêm API để kiểm tra xem users đã cho phép nhận notification từ app Tiki hay chưa

<!-- [ ] Nhờ Hân thêm link tới tài liệu -->

## Hỗ trợ thêm API để trimming Video

<!-- [ ] Nhờ Hân thêm link tới tài liệu -->

## Sửa bug app.onShow

Trước đây, nếu như app A mở ra app B mới.

Khi app B bị close, thì hàm onShow của app A không được gọi.

Trong phiên bản mới, chúng tôi đã sửa lại bug này.

## Sửa lỗi my.reLaunch không truyền được params

Trước đây khi gọi

```
my.reLaunch({ url: 'pages/index/index?a=1' })
```

Thì trong page `pages/index/index` ở hàm onLoad, sẽ không nhận được query string là `a=1`

Trong phiên bản mới, chúng tôi cũng sửa lại API `my.reLaunch` để fix bug này

## Sửa lại hàm `my.getUserInfo`

Trong phiên bản cũ, `my.getUserInfo` trả về `phoneNumber`.

Tuy nhiên, trong lần fix này, chúng tôi sẽ trả về cả trường `phone` và trường `phoneNumber`.

Vui lòng sửa lại API của các bạn để nhận trường `phone`. Trường `phoneNumber` sẽ bị deprecate sau một tháng nữa.

## Sửa lỗi không gọi Component.didUnmount khi page bị remove

Trong các phiên bản cũ, khi một page bị xoá đi, các Component Instance của page đó sẽ không gọi tới hàm didUnmount.

Bug này đã được fix trong phiên bản mới

## Sửa lại cơ chế nhận utm_medium, utm_source

Từ phiên bản mới trở đi, mỗi khi page được navigateTo / reLaunch / redirect, page sẽ nhận được

utm_source, utm_medium từ page đầu tiên khi mở app

Cụ thể nếu app được mở với page `pages/page-a/index` với query string là

```
utm_source=tini-app
```

Sau đó, trong app, khi bạn gọi API `my.navigateTo({ url: 'pages/page-b/index' })`

Hàm `onLoad` của `page-b` sẽ nhận được query string là

```
utm_source=tini-app
```

Nếu như, bạn chủ động truyền vào `utm_source` khi gọi API `my.navigateTo` / `my.redirectTo` / `my.reLaunch`,
thì các giá trị này sẽ được ghi nhận.

## Sửa lại API my.navigationToMiniApp cần backend permission khi truyền vào app meta

Trước đây khi sử dụng `mynavigationToMiniApp`, developers có thể truyền vào trường `appMeta` trong đó các domain
của `appMeta` là sub domain của Tiki.

Từ phiên bản mới, muốn sử dụng `appMeta` các bạn cần có quyền từ backend.

## Sửa lại lỗi khi mở nhiều project

Trong các version cũ, có tình trạng khi mở project A, sau đó người dùng mở thêm project B là project A không xem được simulator.

Bug này đã được fix trong version mới.

## Sửa lỗi ngẫu nhiên không kết nối được tới devtool trên Window

Trong version mới, chúng tôi cũng sửa lỗi không kết nối được tới devtool trên Window

## Hỗ trợ tính năng mới có thể import một project từ Github

Trong version mới, trên Studio sẽ hỗ trợ tính năng import một project từ github url.

Tính năng này sẽ giúp các bạn có thể trải nghiệm các tính năng mới từ trang tài liệu dễ dàng hơn.

Chi tiết có thể xem tại

<https://developers.tiki.vn/docs/introduce/how-to-use-docs/experience-sample-code>

---

# Studio 1.17

## Support thêm API my.chooseVideo

Từ version 1.17, Studio hỗ trợ thêm API để users có thể lấy ra các video từ trong thiết bị.
API có 2 lựa chọn cho users

- chọn video từ album
- chọn video bằng cách quay video, khi quay video bạn có thêm lựa chọn để xác định độ dài của video được quay
  quay

Chi tiết có thể xem tại

<https://developers.tiki.vn/docs/api/media/video/choose-video>

## Support thêm API my.createtInterstitialAd

Chú ý: API đang ở chế độ alpha, sẽ có thêm những thay đổi mới trong tương lai

my.createtInterstitialAd cho phép nhà phát triển có thể hiển thị một banner quảng cáo trong ứng dụng của mình.

Nội dung của banner quảng cáo cũng như việc truy vết xem banner này được bao nhiêu người xem, bao nhiêu lượt click sẽ được Tini App Framework tự xử lý

Chi tiết có thể xem tại

<https://developers.tiki.vn/docs/api/ads/create-interstitial-ad>

## Cho phép thêm lựa chọn injectedScript vào trong web-view component

Component `web-view` được thêm một lựa chọn `injectedScript`.

Với lựa chọn này, nhà phát triển có thể viết các JS script để thay đổi nội dung trang web mà họ muốn hiển thị.

Tuy nhiên, để sử dụng chức năng này, ứng dụng của bạn cần có thêm backendpermission `setWebViewOnLoad`

## Support thêm API để crop image

Chi tiết có thể xem tại

<https://developers.tiki.vn/docs/api/media/image/crop-image>

Đi kèm với API crop image, chúng tôi cũng hỗ trợ thêm component mới <image-cropper> cho phép để hỗ trợ việc crop một ảnh bất kỳ.

Nếu bạn đơn giản chỉ muốn crop hình, bạn có thể sử dụng API my.cropImage.

Tuy nhiên, nếu bạn customize việc crop hình, thì <image-cropper> là dành cho bạn.

Chi tiết về <image-cropper> có thể xem thêm tại
<https://developers.tiki.vn/docs/component/basic/utilities/image-cropper>
Sử dụng component <image-cropper> sẽ phải kèm với jsapi createCropperContext để thực hiện crop hình.
<https://developers.tiki.vn/docs/api/media/image/create-cropper-context>

## Sửa lỗi UI của my.previewImage

Trong phiên bản mới, chúng tôi cũng sửa lỗi khi hiển thị status bar trên Android cho API my.previewImage.

## Hỗ trợ ref một Component bất kỳ

Trong phiên bản mới, chúng tôi hỗ trợ việc tham chiếu tới một component bất kỳ thông qua tham số ref.

Với tham số ref, Page có thể trỏ với component, và gọi các hàm của Component một cách chủ động.

Chi tiết xem tại [https://developers.tiki.vn/docs/framework/component/ref](https://developers.tiki.vn/docs/framework/component/ref)

## Hỗ trợ thêm Component Recycle View

Với `recycle-view` component, Tini App Framework cung cấp giải pháp để cải thiện việc render các list có rất nhiều item.
Chi tiết xem tại [https://developers.tiki.vn/docs/component/basic/view-container/recycle-view](https://developers.tiki.vn/docs/component/basic/view-container/recycle-view)

## Thêm Component Calender

Trong version mới của Tini UI library, chúng tôi cung cấp thêm Component `calendar`
Chi tiết xem tại [https://developers.tiki.vn/docs/component/advance/form/calendar](https://developers.tiki.vn/docs/component/advance/form/calendar)

## Tối ưu việc upload ứng dụng với Studio

Từ version 1.17, khi ứng dụng của bạn vượt quá hạn mức cho phép của Studio, Studio sẽ ngay lập tức thông báo lỗi cho bạn biết, mà không cần phải upload file lên server nữa.

## Sửa lại version của thư viện readable-stream

Từ version 1.17, Tini Studio sẽ sử dụng thư viện readable-stream version 2.0.2.

Thư viện này được tích hợp sẵn cùng với webpack 4.

## Hỗ trợ CSS selector nth-child

Từ version 1.17, Tini Studio sẽ hỗ trợ việc sử dụng các selector nth-child

## Hỗ trợ thêm biến TF_MINIAPP_COMPILER_VERSION

Từ version 1.17, Tini Studio sẽ tự động thêm một biến TF_MINIAPP_COMPILER_VERSION vào các Tini App.

---

# Studio 1.16

## Thêm file project.config.json

Tini Studio hỗ trợ thêm file project.config.json. Ở các phiên bản trước, Tini Studio sẽ tự động tìm kiếm
các thư mục chứa file app.json, và chọn ra thư mục đầu tiên chưa file này để coi đó là root của dự án của bạn.

Ví dụ, dự án của bạn có structure như sau

```
|-- project
  |-- app1
     |-- app.json
  |-- app2
     |-- app.json
```

Nếu Tini Studio được mở với thư mục project, thì Tini Studio sẽ lựa chọn `app1` là root của project của bạn.

Từ version 1.16, các bạn có thể chủ động cấu hình root của thư mục của mình thông qua key "minprogramRoot".

Trong tương lai, Tini Studio sẽ hỗ trợ thêm các cấu hình khác trong file project.config.json này.

Để xem chi tiết, các bạn có thể tham khảo [https://developers.tiki.vn/docs/studio/project-config](https://developers.tiki.vn/docs/studio/project-config)

## Sửa lỗi Simulator không load được khi app.json nhận vào các đường dẫn sai

Trong các version cũ, khi bạn truyền các đường dẫn của page không hợp lệ vào file app.json.
Thì Simulator sẽ không load được, và chỉ hiển thị icon loading mà thôi.
Để tìm hiểu nguyên nhân chi tiết, các lập trình viên sẽ phải vào mục View [ ] Compiler log để xem
các log lỗi từ Compiler.

Từ version 1.16 trở đi, nếu như bạn truyền đường dẫn của pages không hợp lệ vào file app.json,
Simulator sẽ ngay lập tức báo lỗi để bạn biết lỗi ở đâu và sửa file này.

## Sửa lỗi không load được project URL trong tcss

Trong các version cũ, ở tcss, khi bạn truyền vào tcss các file từ trong project.
Ví dụ

```css
.class1 {
  background: lightblue url(../../assets/images/image1.png) no-repeat fixed
    center;
}
```

Thì các file này chỉ được sử dụng trong Tini Studio, mà không có tác dụng khi mở Tini App trên Tiki App.

Từ Tini Studio version 1.16, bug này sẽ được fix. Tính năng này cho phép các bạn có thể load css, hoặc thậm chí
load cả các custom font trong ứng dụng của mình.

## Hiển thị lỗi khi upload Tini App

Trong các phiên bản cũ, khi tổ chức của bạn chưa có bất kỳ ứng dụng nào trên Dev Center, nếu bạn upload Tini App lên,
Studio sẽ tự động mở đường dẫn <https://developers.tiki.vn>

Trong version 1.16, Tini Studio sẽ hiện thị một message để thông báo cho developers tạo mới ứng dụng trên Dev Center

## Hỗ trợ bản build trên Tala

Từ version 1.16, khi muốn mở Studio với môi trường talaria, các bạn có thể sử dụng compiler để truyền vào tham số

```
/Applications/Tini\ App\ Studio.app/Contents/MacOS/Tini\ App\ Studio --args --runtime-env=dev
```

## Sửa lỗi với my.getAuthCode

Trong các phiên bản cũ, khi bạn gọi API `my.getAuthCode`, nếu như bạn đang set appIdentifier trong file package.json
không trùng với một ứng dụng được tạo bảo Dev Center, thì API sẽ trả về token là null.

Ở version 1.16, Tini Studio sẽ trả về error với API này.

## Sửa lỗi API my.getUserInfo luôn trả về trường avatar là ''

Từ version 1.16, khi Tini App chạy trên app Tiki, nếu user có avatar, trường avatar sẽ được trả về trong API my.getUserInfo

## Trả về thêm số điện thoại và email trong API my.getUserInfo

Khi chạy Tini App trên app Tiki, developers có thể xin thêm quyền để lấy thêm số điện thoại và email của users.

Việc xin quyền này cần được approve từ team quản trị của Tini App.

Chi tiết vui lòng xem thêm tại [https://developers.tiki.vn/docs/api/backend-permission](https://developers.tiki.vn/docs/api/backend-permission)

## Fix lỗi với API my.chooseImage

Trong các phiên bản cũ, API my.chooseImage khi chạy trên iOS với tham số `sourceType` bằng `['album']`,
thì sẽ chỉ có thể chọn được các video mà không lựa chọn được image.

Bug này sẽ được fix trên bản mới.

## Thêm API my.setCanPullDown

Từ phiên bản 1.16, developer có thể sử dụng API my.setCanPullDown để set lại việc hỗ trợ kéo xuống để refresh.

Chi tiết về API có thể xem tại <https://developers.tiki.vn/docs/api/ui/pull-down/can-pull-down>

## Thêm API my.setBackgroundTextStyle

Từ phiên bản 1.16, developer có thể sử dụng API my.setBackgroundTextStyle để set lại font và color của text Kéo xuống để refresh.

Chi tiết về API có thể xem tại <https://developers.tiki.vn/docs/api/ui/background/set-background-text-style>

## Thêm API my.setBackgroundColor

Từ phiên bản 1.16, developer có thể sử dụng API my.setBackgroundColor để set màu background của window.

Chi tiết về API có thể xem tại <https://developers.tiki.vn/docs/api/ui/background/set-background-color>

## Yêu cầu phải whitelist domain cho component `web-view`

Từ phiên bản 1.16, khi sử dụng `web-view`, app cần phải white list các domain trước khi sử dụng.

[ ] Nhờ Hồng update thêm tài liệu để whitelist webview

## Hỗ trợ gọi thêm các API mới từ web-view

Từ phiên bản mới, `web-view` component cho phép gọi thêm các API mới.

Hiện tại, `web-view` đã có thể gọi các API sau

- my.navigateTo
- my.navigateBack
- my.getSystemInfo
- my.getUserInfo
- my.request
- my.postMessage
- my.setStorage
- my.getStorage
- my.removeStorage
- my.clearStorage
- my.getStorageInfo
- my.chooseImage
- my.previewImage
- my.getLocation
- my.showLoading
- my.getAddress

Chi tiết xem tại [https://developers.tiki.vn/docs/component/basic/view-container/webview](https://developers.tiki.vn/docs/component/basic/view-container/webview)

## Thêm API my.previewImage

Từ phiên bản 1.16, developer có thể sử dụng API my.previewImage để preview một số ảnh.

Chi tiết về API có thể xem tại [https://developers.tiki.vn/docs/api/media/image/preview-image](https://developers.tiki.vn/docs/api/media/image/preview-image)

## Thêm component rich-text

rich-text component cho phép developer có thể render HTML dưới dạng các nodes

Chi tiết có thể xem tại [https://developers.tiki.vn/docs/component/basic/basic/rich-text](https://developers.tiki.vn/docs/component/basic/basic/rich-text)
