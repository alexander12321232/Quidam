# Quidam 
👋 Hi there! For any professional inquiries or collaborations, please reach out to me at:
megadose@protonmail.com

📧 Preferably, use your professional email for correspondence. Let's keep it short and sweet, and all in English!


![PyPI](https://img.shields.io/pypi/v/Quidam) ![PyPI - Week](https://img.shields.io/pypi/dw/Quidam) ![PyPI - Downloads](https://static.pepy.tech/badge/Quidam) ![PyPI - License](https://img.shields.io/pypi/l/Quidam)
#### For BTC Donations : 1FHDM49QfZX6pJmhjLE5tB2K6CaTLMZpXZ
## Educational purposes only
Quidam allows you to retrieve information thanks to the forgotten password function of some sites.


## 💡 Prerequisite
   [Python 2/3](https://www.python.org/downloads/release/python-370/)
## 🛠️ Installation
### With PyPI
```pip3 install Quidam```
### With Github
```bash
git clone https://github.com/megadose/Quidam.git
cd Quidam/
python3 setup.py install
```
## 📈 Usage
```python
from quidam import *
print(instagram("test"))
print(twitter("test"))
print(github("test"))
```
## 📚 Example
```bash
python3 Quidam.py -u test -m all
```
## Type of information per site:
- Twitter: If the person has not disabled the email option and the last 2 digits of their phone number as well as part of the email the star number ```*``` is the right number corresponding to the email.
- Instagram : Always retrieves a part of the email with the right number of stars and the full domain name
- Github: Go look at recent commits with the api so give the full email and the name associated with the email address.

## Rate limit:
- Twitter rate limit if you do it too fast just change IP
- Instagram no rate limit
- Github no rate limit 
### Demo
![](demo.gif)

## Project example : [Quidam Maltego](https://github.com/megadose/quidam-maltego)

## 📝 License
[GNU General Public License v3.0](https://www.gnu.org/licenses/gpl-3.0.fr.html)
