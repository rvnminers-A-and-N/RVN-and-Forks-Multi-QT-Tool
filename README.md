# RVN-and-Forks-Multi-QT-Tool

## Project Statement
### The tool currently is just windows batch script based and revolves around three modules; the qt-installer and the qt-launcher and qt-closer modules! There are plans to release Linux/MacOS/RPi versions very soon! Also plans for an eventual non-CMD based, GUI experience, all of which will be contained to one window with multiple tabs for each coin; at least this is the first vision!

## Supported Coins
	This was a tool in which I felt was useful for the installation and running of multiple QT wallets at once
	It is based around RVN and its forks! Currently the tool supports the following forks:
		Ravencoin (RVN)
		Ritocoin (RITO)
		Pigeoncoin (PGN)
		Raptoreum (RTM)
		Avian (AVN)
		Ravencoin Dark (XRD)
		Foxdcoin (FOXD)
	
	Please reach out and ask us to add more forks as they come, we are more than willing to add these! 
	Reach out if support for Bitcoin (BTC), Etherum (ETH), Litecoin (LTC), Ethereum Classic (ETC), Dash (DASH), Doge (DOGE), or others are desired! 
	We have considered producing a mass scale version as we upgrade and would be happy to add any desired coins as requested!

### THIS PROCESS IS NOW AUTOMATED FROM USER INPUTS WITHIN THE TERMINAL!!!	

	## User Specific Necessesary Tweaks!!! (THIS WILL BE AUTOMATED SOON BY USER INPUTS IN THE TERMINAL AS PROMPTED)
	
	Find each your_user_here line of each directory pathway and specify your appropriate user based on your system specification!
	
	The Wallet directory can also be modified in the following lines:
	
	:MAKE_DIR
	ECHO MAKING WALLET DIRECTORY...
	mkdir C:\Users\your_user_here\Desktop\Wallets
	ECHO WALLET DIRETCORY MADE!
	GOTO RVN

	Change the \Desktop\Wallets line to whatever you like, however... 
	you MUST update this directory across all calls to it in both batch files when doing this!

	### Edit with appropriate tweaks first! From there, run the qt-installer, then qt-run!!!

### ***Download this package by clicking the green code button towards the top of the page, and then click download zip, you can unzip this package using winrar, 7z, or the windows extraction tool, PLEASE CHECK TO BE SURE that the extracted folder is called RVN-and-Forks-Multi-QT-Tool, and is located on the desktop. The extracted folder may contain a duplicate directory with all files in it, just copy this to the desktop and give it the appropriate name. It should contain the windows bash script directory with the three .bat files inside, and this README.md. Just like the repo structure. The idea is the system should be able to find (C:\Users\user userprofile path will vary)\Desktop\RVN-and-Forks-Multi-QT-Tool\Windows Bash Scripts so that the three .bat files can be opened and worked.***

### If you have any pre-existing wallets, back them up!!!! Sometimes when a new qt wallet version is downloaded and opened, it can corrupt an older wallet version file and cause havoc; I myself have been in this spot, I was able to fix my mistake thankfully, but avoid it!

### Roadmap
	-Automate user specific tweaks with starting by defining the user and the desired working directory location at the very beginning (COMPLETE)
	-Give the .bat files icons (this may have to wait until the multi-qt.exe phase)
	-Use qt-creator or another qt tool to produce a single window, tab based experience in which a user can switch back and forth between coins;
	when it starts up, the user will be greeted with a checklist of the different coins and can select the desired ones for opening
	-Will be a downloadable release package just like on the github of the coins themselves, consisting of an install/uninstall and multi-qt.exe
	-A main working directory containing the wallets of each folder will be produced, each of which sorted in their own directories 

## Feel free to reach out for support at our discord server! 
	https://discord.gg/BGVNaKfkBP

## Donation addresses:
	RVN:
	RITO:
	PGN:
	RTM:
	AVN:
	XRD:
	FOXD:
	
	All will be added very soon, thank you!!!

# THANK YOU AND ENJOY!!!
