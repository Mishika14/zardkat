# Circuit using Circom and testing it through the polyscan network
In this project implementation of the following circuit has been done
![image](https://github.com/Mishika14/zardkat/assets/95122524/9d179758-d798-4e58-a06f-b157c435c7ec)
The logic for this code is given in the circuit.com file 
To deploy this use the following commands:-
1) npm i
2) npx hardhat circom
3) npx hardhat run scripts/deploy.ts
4) or on some blockchain polygon network for example mumbai rpc network
5)npx hardhat run scripts/deploy.ts --network mumbai
6) copy the adresss at which the contract is deployed 
7) paste it into the ploygon scan mumbai testnet network
8) voila, you will se the transaction details there!
