A very simple script for an NFT commity-reveal scheme. 

Prior to usage, commit unshuffled NFT metadata to ERC-721 smart contract and upload all images.

Uses the VRF to generate a seed. Then use pandas to shuffle pre-committed metadata. Then convert shuffled metadata to JSON which is uploaded to IPFS. Then call setBaseURI on the NFT to change metadata to the shuffled data. 

use NFT_metadata_refresher to refresh the metadata and images for your entire collection on OpenSea. 


Check our Medium post for more details: https://medium.com/@convexlabs/how-to-verify-that-honestnft-vigilantes-are-randomly-distributed-2592665c5c72

