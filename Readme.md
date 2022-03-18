Steps to tryout Web3 Storage on filecoin

#Complete the dependency installation
npm install

#Get API Token
1. Create API token in https://web3.storage/account
2. Give name of the API token and click create
3. Copy and keep it safe we'll use shortly

#You can import the files to Filecoin using below command by providing the token and files that needs to be stored, we can upload multiple files or directory too
node put-files.js --token=<YOUR_TOKEN> ./filename1 ./filename2 ./filenameN

#We'll receive a response similar to below, copy the CID to valiate the files thats uploaded
Content added with CID: bafybeiabgzcor46z7lfj7zcgjzrr2gq4nug2iwdr6ngkwyrkznkljnagr4

#Validate you file, replace YOUR_CID with CID from the response you received
Go to https://dweb.link/ipfs/YOUR_CID

or you can validate in the UI of the https://web3.storage/account