SeekCAM


<C# Setting>


sudo apt-key adv --keyserver hkp://keyserver.ubuntu.com:80 --recv-keys 3FA7E0328081BFF6A14DA29AA6A19B38D3D831EF

echo "deb http://download.mono-project.com/repo/debian raspbianstretch main" | sudo tee /etc/apt/sources.list.d/mono-official.list

sudo apt-get update

sudo apt-get install mono-devel --yes --allow-unauthenticated

[출처] 윈도우에서 작성한 C#과 .NET 라즈베리파이에서 실행하기|작성자 초초
