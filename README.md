# Employee-review-system
This application has following features with three views
1. Admin view
```sh
Add/remove/update/view employees
Add/update/view performance reviews
Assign employees to participate in another employee's performance review
```
2. Employee view
```sh
List of performance review requiring feedback 
An employee can register, only admin can make an employee an admin
```
3. sign in for admin and user.
```sh
also has super user for initialting the application once
Make 1 login for admin and employee
```

## How to setup on local machine
1. To use this repository your machine should have [node](https://nodejs.org/en/), npm, [monogodb](https://docs.mongodb.com/manual/installation/) and [git](https://git-scm.com/downloads). to check version exicute these.


2. Now clone this repository
git clone https://github.com/ameet99/employeeReviewSystem.git

3. Change directory to Ecomerce-API
cd employee-review-system

3. Install dependencies
npm install --save
4. Start mongo db this command may differ... system to system.
sudo systemctl start mongod
5. That's... it  run the application
npm start

This Project is developed by Amit Bhavsar