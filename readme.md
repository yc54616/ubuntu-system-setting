ubuntu 22.04 english -> normal install, wift connect after utility install

sudo nopassword 설정

1. ubuntu software update

2. kaist mirror server change
sudo vi /etc/apt/sources.list
:%s/kr.archive.ubuntu.com/ftp.kaist.ac.kr
:%s/security.ubuntu.com/ftp.kaist.ac.kr
sudo apt-get update && sudo apt-get upgrade -y && sudo apt-get autoremove -y

3. 한글 변환 + 한글 입력기
https://staraube.tistory.com/105

홈폴더 설정 super + e
캡처 super + shift + s
알림 사용안함


4. program install 
chrome

htop

vmware
https://github.com/hegdepavankumar/VMware-Workstation-Pro-17-Licence-Keys
sudo sh vmware[~].bundle
sudo apt install gcc-12 g++-12
vmware -> secure boot -> 17.5.1 최신버전
[https://www.bearpooh.com/25](https://blog.kimzuni.com/posts/vmware-kernel-module-updater-error/) (vmmon error)
https://m.blog.naver.com/snova84/223393374449 (속도 빠르게)

카카오톡 -> wine
https://goyunji.tistory.com/154 (wine install)
https://ashton0410.tistory.com/entry/ubuntu%EC%9A%B0%EB%B6%84%ED%88%AC-wine%EC%99%80%EC%9D%B8-%EC%84%A4%EC%B9%98-%EB%B0%8F-%ED%94%84%EB%A1%9C%EA%B7%B8%EB%9E%A8-%EC%B6%94%EA%B0%80-%EC%82%AD%EC%A0%9C-%ED%95%9C%EA%B8%80-%EA%B9%A8%EC%A7%90-%EB%B2%84%EC%A0%BC%ED%99%95%EC%9D%B8 (작업 관리자 한글) -> malgun.ttf 받아서 굴림대신 넣기

discord, spoitfy, vscode, docker, rstudio, 

5. gnome look-org
https://techhut.tv/favorite-gnome-gtk-themes-icons/
dash to dock
https://brown.ezphp.net/entry/Ubuntu-Dash-to-Dock-%EC%A4%91%EB%B3%B5-%ED%91%9C%EC%8B%9C-%EB%AC%B8%EC%A0%9C-%ED%95%B4%EA%B2%B0
https://www.gnome-look.org/p/1357889

6. zsh setting
https://medium.com/@satriajanaka09/setup-zsh-oh-my-zsh-powerlevel10k-on-ubuntu-20-04-c4a4052508fd
https://heetop.github.io/Ubuntu-ZSH-Setting/

