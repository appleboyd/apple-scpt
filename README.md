项目是软件数据备份使用哈


<img width="225" height="170" alt="截屏2026-01-09 15 13 41" src="https://github.com/user-attachments/assets/b88f3805-7b0f-48ff-b248-34162edd71dc" />

               
<img width="223" height="161" alt="截屏2026-01-09 15 13 24" src="https://github.com/user-attachments/assets/7e4bc90f-763d-4da1-ae1f-5c89fd99bccc" />




没有标签🏷️类：  
set websiteList to {"URL","URL","URL",}                 
                                                 
tell application"浏览器/打开运行的app"                            
     activate                           
	 repeat with website in websiteList                          
	        open location website                                          
	end repeat                                                  
end tell                      
