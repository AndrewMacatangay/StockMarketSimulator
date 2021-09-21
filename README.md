# Stock Market Simulator
This repository contains a stock market simulator which scrapes data from Yahoo Finance's API and implements a client(s)-server interaction. Along with this, a login feature was added so that a user can register, log in, and paper trade with their portfolio saved into a personal CSV file. Cryptocurrencies are supported.
<br>
The original code can be found [here](https://github.com/AndrewMacatangay/Concurrency/tree/main/Multithreading/Projects/Project2), but was moved to it's own repository after seeing how large of a project it became.
## Installing and Running

```
git clone https://github.com/AndrewMacatangay/StockMarketSimulator
```
To run the program, you will need at least two console windows - one to run the server and the other to run the client:
```
make runServer
make runClient
```
Additionally, if you'd like to run multiple clients, you may use [tmux](https://github.com/tmux/tmux/wiki). Installation is as follows:
```
sudo apt-get install tmux
```
## Commands
In total there are 12 commands. The first 5 commands do not require the user to be logged in. The last 5 commands are reserved for users that are logged in.
<p align="center">
  Each command can be seen by running the "help" command
  <br><br>
  <img src="https://user-images.githubusercontent.com/61638274/134079766-47c49e26-eaad-459a-8425-99d1a497df6c.png" alt="image" width="250"/>
</p>
<br><br>
<p align="center">
  &lt;ticker&gt; - Enter a ticker symbol to get basic information about it
  <br><br>
  <img src="https://user-images.githubusercontent.com/61638274/134081439-5aadc637-e8d5-483c-b4a8-fc1caca93ae5.png" alt="image" width = 400/>
</p>
<p align="center">
  &lt;ticker&gt; today - Enter a ticker symbol to get information about today's prices
  <br><br>
  <img src="https://user-images.githubusercontent.com/61638274/134102493-b3822925-806a-4911-bca9-86eb68744dd8.png" alt="image" width = 400/>
</p>
<p align="center">
  &lt;ticker&gt; day averages - Enter a ticker symbol to get the 50 and 200 day averages
  <br><br>
  <img src="https://user-images.githubusercontent.com/61638274/134104997-f4fdc76f-6e42-4a27-9dd8-5eea0e1a3c7c.png" alt="image" width = 400/>
</p>
<p align="center">
  &lt;ticker&gt; volumes - Enter a ticker symbol to get the various averages
  <br><br>
  <img src="https://user-images.githubusercontent.com/61638274/134105658-70f69afd-c38c-4a49-8297-23fa2746a29e.png" alt="image" width = 400/>
</p>
</p>
<p align="center">
  &lt;ticker&gt; year - Enter a ticker symbol to get yearly information
  <br><br>
  <img src="https://user-images.githubusercontent.com/61638274/134105824-2fa69e51-aa59-4a59-9e54-e02226bd4148.png" alt="image" width = 400/>
</p>
