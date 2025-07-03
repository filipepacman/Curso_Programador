    ✅ No Debian, Ubuntu, Mint (arquivo .deb baixado)

1️⃣ Vá até a pasta onde você baixou (normalmente ~/Downloads):

cd ~/Downloads

2️⃣ Instale o arquivo .deb (substitua code_x.y.z_amd64.deb pelo nome exato do arquivo que você baixou; use ls para ver):

sudo apt-get update
sudo dpkg -i code\*.deb

3️⃣ Se aparecerem erros de dependências, corrija com:

sudo apt-get install -f

---

✅ No Fedora, RHEL, openSUSE (arquivo .rpm baixado)

sudo dnf update

1️⃣ Vá para a pasta de downloads:

cd ~/Downloads

## 2️⃣ Instale o arquivo .rpm com seu gerenciador:

    No Fedora/RHEL/CentOS (com dnf):

sudo dnf check-update
sudo zypper install code*.rpm
sudo dnf install code*.rpm

---

    Ou se ainda usa yum:

sudo yum check-update
sudo yum update

sudo yum localinstall code\*.rpm

---

    No openSUSE (com zypper):

✅ openSUSE

    sudo zypper refresh:


    sudo zypper update:

## sudo zypper install code\*.rpm
