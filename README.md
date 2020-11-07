# Pocket IMS

PocketIMS is a better implementation of [UIMS-API](https://github.com/cu-unofficial/uims-api), this project picks up where [SnapAttendance](https://github.com/xpt1x/SnapAttendance/) leaves off and aims to provide faster access to important modules from CUIMS ( `Chandigarh University Information Management System`) with a better UI and UX.  
Application has a minimal UI built with ReactJS, MaterialUI. User's data is not kept on any server or DB, its stored locally on user's end

## Test Run

### **Stable**: https://ims.snapatd.tech  
**Beta**: https://beta.snapatd.tech

## Contributions

If you want to help this project, then you just have to use and report problems you faced.
Contributions are **most** welcome and active contributors are required to keep this project alive.

## Building

**Npm, Python3** is required

```bash
$ git clone https://github.com/xpt1x/PocketIMS.git
$ cd PocketIMS
# install required dependencies
$ pip install -r requirements.txt
# install uims-api module
$ pip install .
# running backend server
$ cd frontend
# install required dependencies
$ npm install
$ npm run start
$ cd ..
$ export FLASK_APP=application.py
$ flask run