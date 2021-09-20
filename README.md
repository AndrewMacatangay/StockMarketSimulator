# Stock Market Simulator
Stock Market Simulator using Yahoo Finance API with client/server networking capabilities along with account login features
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
In total there are 12 commands. The last 5 commands are reserved for users that are logged in. The first 5 commands do not require the user to be logged in. 
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
