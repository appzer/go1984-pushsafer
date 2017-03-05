![Pushsafer](https://www.pushsafer.com/de/assets/logos/logo.png)
# go1984-pushsafer
##How to send push-notifications out of go1984
go1984 was designed for professional and problem-free video surveillance and recording. The easy to use video surveillance software with varied functions at an absolutely competitive price sets a new standard for the software industry.

[Pushsafer.com](https://www.pushsafer.com) make it easy and safe to send &amp; receive push-notifications to your
- Android devices
- iOS devices (iPhone, iPad, iPod Touch, Watch)
- Windows 10 Phone & Desktop
- Browser (Chrome & Firefox)

## Usage
1. copy the file [callurl.cmd](https://github.com/appzer/go1984-pushsafer/blob/master/callurl.cmd) to a desired path on you PC
2. callurl.cmd is a small batch program that can open urls in background
3. Open Alarm Management of your desired camera in go1984 ![Pushsafer](https://www.pushsafer.com/en/assets/examples/go1984_push-notification-1.jpg)
4. enter the program file path
5. the programm file path is the path of callurl.cmd on your pc + the Pushsafer API url with required key and optional parameter in quotation marks
6. you can use the Link/URL generator in your dashboard
7. choose parameters you want and click on Create Link
8. Copy the generated URL in go1984

## Example program file path

	{path to callurl.cmd} "{Pushsafer API URL}"
  
	D:\callurl.cmd "https://www.pushsafer.com/api?k=XXXXXXXXXXXXXXXXXXXX&d=269&i=82&s=25&v=3&t=go1984%20Alarm&m=Motion%20detection%20Living%20room"
  
## Screenshots of go1984 Push-Notifications

Screenshot Client App

![Pushsafer](https://www.pushsafer.com/de/assets/examples/go1984_push-notification-2.jpg)

Screenshot iOS > iPhone

![Pushsafer](https://www.pushsafer.com/de/assets/examples/go1984_push-notification-3.jpg)

Screenshot Android

![Pushsafer](https://www.pushsafer.com/de/assets/examples/go1984_push-notification-4.jpg)

Screenshot Windows 10 Phone

![Pushsafer](https://www.pushsafer.com/de/assets/examples/go1984_push-notification-5.jpg)

Screenshot Windows 10 Desktop

![Pushsafer](https://www.pushsafer.com/de/assets/examples/go1984_push-notification-6.jpg)
