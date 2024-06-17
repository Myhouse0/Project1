// Create an array to store your NFTs let myNFTCollection = [];

// Function to create an NFT with the given parameters and add it to the collection function createNFT(title, details, imgURL) { let nft = { title: title, details: details, imgURL: imgURL }; myNFTCollection.push(nft); }

// Function to iterate over the NFT collection and log each NFT's metadata function displayNFTs() { myNFTCollection.forEach((nft, index) => { console.log(NFT #${index + 1}); console.log(Title: 
{nft.details}); console.log(Image URL: ${nft.imgURL}); console.log("------------------------"); }); }

// Function to log the total number of NFTs created function showTotalSupply() { console.log(Total number of NFTs: ${myNFTCollection.length}); }

// Calling the functions to create and display NFTs createNFT("Unique Art 1", "Description for Unique Art 1", "unique1.jpg"); createNFT("Unique Art 2", "Description for Unique Art 2", "unique2.jpg"); createNFT("Unique Art 3", "Description for Unique Art 3", "unique3.jpg");

displayNFTs();

showTotalSupply();
