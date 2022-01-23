<div id="top"></div>


<!-- PROJECT LOGO -->
<br />
<div align="center">
    <img src="images/to do icon.jpg" alt="Logo" width="500" height="400">
  
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
        <li><a href="#introduction">Introduction</a></li>
        <li><a href="#features">Features</a></li>
        <li><a href="#To-Do-header">To Do Header</a></li>
        <li><a href="#To-Do-cpp">To Do Cpp</a></li>
        <li><a href="#forms">Forms</a></li>
  </ol>
</details>

- # [Introduction](#Introduction)
 Everyone has things to do, and we all seem to need help getting them done.To Do Application help you to  manage your tasks and store an archive of all the pending and finished tasks.

- # [Features](#Features)
This application makes you comfortable, you can start each day with peace of mind by clearly visualizing the tasks in progress. also it gives you the opportunity to focus on what matters and save all your ideas to do in the future.
##  **In our Application we have :**

 -Menu Bar.
 
 -Tool bar.
 
 -Status bar to print the informations.
 
 
## **the application looks like that :**
<p align="center">
     <img src="images/logo.png">
   </p>

  - ## [To Do Header](#To-Do-Header)
    - ### [ MainWindow header](#MainWindow-header)
    - ### [ AddDiaolg header](#AddDiaolg-header)
   
   # To Do Header
## MainWindow header
 ### Functions
```c++

class MainWindow : public QMainWindow
{
    Q_OBJECT

public:
    MainWindow(QWidget *parent = nullptr);
    ~MainWindow();
    void makeConnexions();
    void chargerTasks(QString myFile);
    }
```
 ### Private Slots
 ```c++
private slots:

    void on_actionAdd_Task_triggered();

    void on_actionTask_Done_triggered();

    void on_actionPending_Task_triggered();

    void on_actionClose_triggered();

    void on_actionabout_Qt_triggered();

    void on_actionabout_triggered();

private:
    Ui::MainWindow *ui;
    
```
## AddDiaolg header
  ### Functions
```c++
class addDialog : public QDialog
{

    Q_OBJECT

public:
    explicit addDialog(QWidget *parent = nullptr);
    ~addDialog();

    QString getDescription();
    QString getTag();
    QString getFinished();
    QDate getDueDate();
    void showEvent(QShowEvent * event);


private:
    Ui::addDialog *ui;

};

```

  - ## [To Do Cpp](#To-Do-Cpp)
    - ### [ MainWindow Cpp](#MainWindow-Cpp)
    - ### [ AddDiaolg Cpp](#AddDiaolg-Cpp)
    - ### [ Main Cpp](#Main-Cpp)
        
# To Do Cpp
 ##   MainWindow Cpp

  ```c++ 


```
 ##  AddDiaolg Cpp
 ```c++

```
##  Main Cpp
 ```c++

```


 - ## [Forms](#forms)
    - ### [ MainWindow ui](#MainWindow-ui)
    - ### [ AddDiaolg ui](#AddDiaolg-ui)
       
        
# Forms
 ##   MainWindow ui
 
<!-- PROJECT LOGO -->
<br />
<div align="center">
    <img src="images/to do icon.jpg" alt="Logo" width="500" height="400">
  
</div>

 ##  AddDiaolg ui
 
 <!-- PROJECT LOGO -->
<br />
<div align="center">
    <img src="images/to do icon.jpg" alt="Logo" width="500" height="400">
  
</div>





Our Team -[DARBAL nour-elhouda](https://github.com/teamkhaoulanour) -[MZOUDI Khaoula](https://github.com/KhaoulaMzoudi)

Project Link: [To Do](https://https://github.com/Darbal-Nour-elhouda/To-Do/new/main)

Encadré par : [Mr.Belcaid Anass](https://)


<p align="right">(<a href="#top">back to top</a>)</p>
