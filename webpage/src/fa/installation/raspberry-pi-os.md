# نصب در سیستم عامل رزبری پای

## سیستم عامل رزبری پای 11

فرمان های پوسته زیر را برای اطمینان از مخزن اجرا کنید.

```bash
wget http://download.opensuse.org/repositories/home:/pbek:/QOwnNotes/Raspbian_10/Release.key -O - | sudo apt-key add -
```

فرمان های پوسته زیر را برای افزودن مخزن اجرا کرده و QOwnNotes را از آنجا نصب کنید.

```bash
sudo bash -c "echo 'deb http://download.opensuse.org/repositories/home:/pbek:/QOwnNotes/Raspbian_10/ /' >> /etc/apt/sources.list.d/qownnotes.list"
sudo apt-get update
sudo apt-get install qownnotes
```

[بارگیری مستقیم](https://download.opensuse.org/repositories/home:/pbek:/QOwnNotes/Raspbian_11)

## سیستم عامل رزبری پای 10

فرمان های پوسته زیر را برای اطمینان از مخزن اجرا کنید.

```bash
wget http://download.opensuse.org/repositories/home:/pbek:/QOwnNotes/Raspbian_10/Release.key -O - | sudo apt-key add -
```

فرمان های پوسته زیر را برای افزودن مخزن اجرا کرده و QOwnNotes را از آنجا نصب کنید.

```bash
sudo bash -c "echo 'deb http://download.opensuse.org/repositories/home:/pbek:/QOwnNotes/Raspbian_10/ /' >> /etc/apt/sources.list.d/qownnotes.list"
sudo apt-get update
sudo apt-get install qownnotes
```

[بارگیری مستقیم](https://download.opensuse.org/repositories/home:/pbek:/QOwnNotes/Raspbian_11)

## رزبین 9.0

فرمان های پوسته ای زیر را برای اطمینان از مخزن اجرا کنید.

```bash
wget http://download.opensuse.org/repositories/home:/pbek:/QOwnNotes/Raspbian_9.0/Release.key
-O - | sudo apt-key add -
```

فرمان های پوسته ای زیر را برای افزودن مخزن اجرا کرده و QOwnNotes را از آنجا نصب کنید.

```bash
sudo bash -c "echo 'deb http://download.opensuse.org/repositories/home:/pbek:/QOwnNotes/Raspbian_9.0/ /' >> /etc/apt/sources.list.d/qownnotes.list"
sudo apt-get update
sudo apt-get install qownnotes
```

[دانلود مستقیم](https://download.opensuse.org/repositories/home:/pbek:/QOwnNotes/Raspbian_11)
