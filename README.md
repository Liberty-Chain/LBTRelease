# LBTRelease
###On Linux:
* To git clone,run:
'''
git clone https://github.com/Liberty-Chain/LBTRelease.git
'''
* Change to the cloned directory, run:
'''
cd LBTRelease/release/Linux/bin
'''
* Run node program through stagenet,run:
'''
./libertyd --stagenet
'''
* Wait for synchronization to complete.
* Run the LBT wallet with a new shell,run:
'''
./liberty-wallet-cli
'''
* Enter the wallet name and password and select the language.
* Keep your seeds.
* Copy your public key,such as [ThisIsADemonstrationPublicKey].
* Change to the node shell and start mining with your public key,run:
'''
start_mining [ThisIsADemonstrationPublicKey] [Enter the number of your CPU cores]
'''  
###On Windows:
* To git clone,run:
'''
git clone https://github.com/Liberty-Chain/LBTRelease.git
'''
* Change to the cloned directory, run:
'''
cd LBTRelease/release/Windows/bin
'''
* Run node program through stagenet,run:
'''
libertyd.exe --stagenet
'''
* Wait for synchronization to complete.
* Run the LBT wallet with a new shell,run:
'''
liberty-wallet-cli.exe
'''
* Enter the wallet name and password and select the language.
* Keep your seeds.
* Copy your public key,such as [ThisIsADemonstrationPublicKey].
* Change to the node shell and start mining with your public key,run:
'''
start_mining [ThisIsADemonstrationPublicKey] [Enter the number of your CPU cores]
'''