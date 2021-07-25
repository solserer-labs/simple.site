### Guide to uploading content and viewing it on sol.place

0. Check out the example -> [grandrising.sol.place](https://grandrising.sol.place)

1. Clone this repo
```
git clone https://github.com/solserer-labs/simple.site.git
```
2.  Install https://github.com/ipfs-shipyard/ipfs-deploy
```
npm install -g ipfs-deploy
```
3. Upload to infura. 
```
ipd build/
```
4. [Upload](https://docs.bonfida.org/help/edit-a-domain-name) your content ID to your solana domain name.  The content data structure should look like this:
```
{"ipsp":"your-content-hash-here"}
```
![image](https://user-images.githubusercontent.com/81876372/126907920-0c66c1ba-5aa2-4226-8d07-4659222ccc9c.png)
5. That should be it for now. You should be able to see your site at your-domain.sol.place. 

