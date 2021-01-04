
## P2P_Reward

P2P_Reward [type] if(type == 1){ [Your_Wallet_Address] [Your_Wallet_privateKey] }

if type = 1, need arguments(Your_Wallet_Address and Your_Wallet_privateKey)<br>
if type = 2, it will used already inputted data(Your_Wallet_Address and Your_Wallet_privateKey)


[examples]

	type is 1 = P2P_Reward.exe 1 Your_Wallet_Address Your_Wallet_privateKey
	type is 2 = P2P_Reward.exe 2


## P2P_CLI_Process
index-win.exe -> P2P_CLI_Process

pro 입력시 Provider 로 작동
req 입력시 Requester로 작동

info  :  help<br>
P2P DSC : command List   :<br>
pro : select provider mode - to give resource<br>
req : select requester mode - to start project<br>
start : start  after select mode<br>
show_w : showing wallet address<br>
CRE_W_A : creating wallet<br>
CRE_W_A_F : force creating wallet<br>
checkbalance_X : X - 0 : DSCT, X - 1 : CONT<br>
WAL_XXXXXXXXXXXXXXXXXX : overwrite wallet with XXXXXXXXXXXXXXXXXXX<br>
provider mode : pro -> select project -> start<br>
requester mode : req ->start(it need project.json)<br>



## Conun_P2P Setup File
### :rocket: Release
Download Link: [Click](https://docs.conun.io/files/Conun_P2P_Setup.exe)<br>
Released since 2021.01
