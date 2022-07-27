## Binance API Future Trading Program 

Having experienced Binance futures trading and securities company derivatives trading, it was recognized that there was not a large difference in the volume of transactions, and that the execution rate of Binance futures was relatively slow. I realized that I needed to create a trading program using an API to speed up execution. 

### 1. Purpose 
- I feel frustrated with the Binance Futures UI and implement it in the same UI as the HTS Derived Futures Hogachang in Korea 
- Offered for investors who want to make automatic trades but do not know the main methods 
- coin-m, usd-m can be changed when creating Binance objects

 ### 2. UI Interface
  ---- 
![KakaoTalk_20220209_235029338](https://user-images.githubusercontent.com/40832965/153558802-e102a735-e89e-4f79-bb4d-29ef26cee503.png)
  ---- 
  
  ### 3. Demo VIdeo 
  - Black window under UI is Binance window 

  https://user-images.githubusercontent.com/40832965/157466507-d5f65489-a3d6-42a5-9f29-00caeca9eb17.mp4
  
  
  ### 4. Overview 
  - If you select the coin name in the coin gift setting bar, the corresponding coin bid window will be printed 
  - 1 LONG position of coins when you click the buy button 
  - 1 SHORT position of coins when you click the sell button 
  - Cancel Batch Orders Cancel All Orders 
  - If you want to create an automatic trade, you can do so by using the above method. 
  
  ### 5. Requirements 
  - Register the Future API on the binance site (create and save the "api.txt" file) 
  - Python3, PYQT, QTdesigner