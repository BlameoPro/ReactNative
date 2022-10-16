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
