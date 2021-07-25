### Guide to uploading content and viewing it on sol.place

1.  Install https://github.com/ipfs-shipyard/ipfs-deploy
```
npm install -g ipfs-deploy
```
2. Upload to infura. 
```
ipd build/
```
3. [Upload](https://docs.bonfida.org/help/edit-a-domain-name) your content ID to your solana domain name.  The content data structure should look like this:
```
{"ipsp":"your-content-hash-here"}
```
![image](https://user-images.githubusercontent.com/81876372/126907920-0c66c1ba-5aa2-4226-8d07-4659222ccc9c.png)
4. That should be it for now. 
