> [Visit React Native Docs](https://reactnative.dev/docs/environment-setup)

# Download Android Studio

> [Download](https://developer.android.com/studio?gclid=Cj0KCQjw166aBhDEARIsAMEyZh6Fbl62brLWn1gN8mRijFWJ3l7Du1sj6R2EOKvNkoRPo7JUQJPZWLEaAuu6EALw_wcB&gclsrc=aw.ds)


> Step 1: Download thành công tiến hành cài đặt, đảm bảo đã tích chọn những options sau:

  - Android SDK
  - Android SDK Platform
  - Android Virtual Device


> Step 2: Click vào SDK Mangager, và download từng phần về.
![image](https://user-images.githubusercontent.com/115060017/196032062-8a81a89b-3621-4fd6-a042-6fc8bfefbc74.png)
![image](https://user-images.githubusercontent.com/115060017/196032376-f2654636-ce80-42bc-90d0-a0dfdc7d327e.png)
![image](https://user-images.githubusercontent.com/115060017/196032478-d69861e6-eff8-434f-b715-d47a01684238.png)


# Setup on window

- Step 1: Mở Power Shell với quyền admin:

```
choco install -y nodejs-lts openjdk11

```

*Nếu có lỗi "choco not found", gặp lệnh sau:*
```
Set-ExecutionPolicy Bypass -Scope Process -Force; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))
```

- Step 2: Sau khi đã cài đặt được android studio và xong bước 1, thiết lập biến môi trường cho android để chạy:
  - Mở **Windows Control Panel** (1)
  - Click **User Accounts**, sau khi vào chi tiết bên trong thì click tiếp vào **User Accounts** (2)
  - Click vào **Change my environment variables**(3)
  - Click vào **New...** và tạo 1 biến môi trường tên là *ANDROID_HOME* và đường dẫn value tới *android sdk*.
  - ![image](https://user-images.githubusercontent.com/115060017/196032851-c4b8403a-c99e-476a-ab7a-c7534ea8a0c2.png)
  - Thêm platform-tools vào Path ( tương tự từ Step 2.1 tới Step 2.3 )
  - Chọn biến **Path**
  - Click vào **Edit**
  - Cick vào **New**
  - Thêm đường dẫn *%LOCALAPPDATA%\Android\Sdk\platform-tools* vào và lưu lại.

- Step 3: Sau khi hoàn thành các bước xong, tiến hành tạo máy ảo.
  - ![image](https://user-images.githubusercontent.com/115060017/196033491-be0adb3b-0643-4dc2-af98-80ba93c63672.png)
  - Mặc định nó sẽ tạo sẵn cho 1 device, có thể select vào device đó và nhấn start để chạy máy ảo.
  - ![image](https://user-images.githubusercontent.com/115060017/196033526-30cf36dd-ae30-47c1-807c-c953a8a0e87d.png)
  - Để tạo device mới, click vào **Create device** sau đó sẽ hiện ra một cửa sổ cho phép chọn thông tin để tạo device.
  - ![image](https://user-images.githubusercontent.com/115060017/196033559-b69ecca2-32bc-4c4f-9443-52f10000af75.png)
  - Sau khi chọn device thành công, bấm **Next** để chuyển sang cửa sổ chọn hệ điều hành, lưu ý, nếu hệ điều hành chưa được tải xuống thì bấm tải sau đó select và next.
  - ![image](https://user-images.githubusercontent.com/115060017/196033606-254a3746-2337-4b66-a95c-5c2ff170be5c.png)
  - Cuối cùng sau khi next sẽ hiện ra cửa sổ của màn hình sửa tên thiết bị + thông số và confirm. 
  - ![image](https://user-images.githubusercontent.com/115060017/196033676-0d716c36-46ec-4eff-ace7-d708cd552779.png)
  - Sau khi tạo thành công và chạy lại sẽ ra kết quả như sau:
  - ![image](https://user-images.githubusercontent.com/115060017/196033754-fbb76e97-e105-47e8-a18f-fa4517e28477.png)


