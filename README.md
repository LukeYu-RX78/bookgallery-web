# bookgallery-web 
A react frontend application with react-router v6 and [Ant design](https://ant.design/) react ui library implements a simple book gallery website  



## About the project
This project is implemented by `React` + `JavaScript`, as the `view` part of the `MVC` structure. It can be simply run by `npm start` after installing the
dependency by `npm install`. <sub>(of course the database, web server, and backend server should be deployed first since the mock data is already deleted)</sub>  
![WeChat50124b1fc4e5f3a232a496edbb19e573](https://github.com/LukeYu-RX78/bookgallery-web/assets/116868785/9e471f46-00c6-42e9-ba24-f03062c08f5e)

###Main page:
The best-selling book carousel based on downloads number.  
<sub>(the order of this carousel could be changed if you keep download any book until it's downloads up to top 4)</sub>
![WeChat7e33e76da002f39091189ecab09309a0](https://github.com/LukeYu-RX78/bookgallery-web/assets/116868785/972a59af-cea6-43ac-a173-1870514ddf9a)

###Book lists page:
showing all books from the database.  
The navigation bar cloud route to to different page <sub>(use React router)</sub>
![WeChat4b14bfb35c54000dbec77d2c1ea7c46d](https://github.com/LukeYu-RX78/bookgallery-web/assets/116868785/c793e32c-ac8d-4742-8b71-cd6bc0cfcb42)

Start downloading the pdf file after clicking the download link:  
<sub>(the `downloads` attr would also increase in the database which could change the main page carousel order)</sub>
![WeChat494b4e90a1be43acd1804f08100ce22e](https://github.com/LukeYu-RX78/bookgallery-web/assets/116868785/af54bfa8-892a-449f-9d12-630e54065cfb)

Clicking delete would delete the book from the database and refresh the page.  
<sub>(the third page only have one book, so after delete it, the pagination would only shows two pages)</sub>  
![2371696561744_ pic](https://github.com/LukeYu-RX78/bookgallery-web/assets/116868785/f7cd9248-5dfd-4496-b00d-f664ed784d29)  
![2381696561787_ pic](https://github.com/LukeYu-RX78/bookgallery-web/assets/116868785/052ecfd0-3cda-4dfa-a596-400bc9ae2512)  


