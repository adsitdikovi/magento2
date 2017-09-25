# magento2

 #### Magento 2 DevOpps (Installation and setup)
 
 #### 1
 Composer installation
 
 #### 2
 Setup Brew: 
 ```
  ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"  
  brew update brew tap homebrew/dupes  
  brew tap homebrew/php     
  brew install php70   
  brew install mcrypt php70-mcrypt   
  Finally, install composer: brew install composer  
  ```
#### 3 
Create account in Magento width authorization keys  

  composer create-project --ignore-platform-reqs --repository-url=https://repo.magento.com magento/project-edition magento2
#### 4
  Username: public key from magento Password: private key from magento
#### 5
 composer require --ignore-platform-reqs arvatoscm/dockerize-magento2 chmod +x bin/console
#### 6
 Add host in hosts file
#### 7
 sudo nano /etc/hosts
#### 8
 192.168.1.143 magento2.localhost
#### 9
 .bin/console install magento2.localhost
#### 10
 Installation complete.
 
 Frontend http://magento2.localhost/ Backend https://magento2.localhost/management   
 Username: admin Password: enAVINa2s