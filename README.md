项目是软件数据备份使用哈



没有标签🏷️类：                  

set websiteList to {"URL","URL","URL",}                 
                                                 
tell application"浏览器/打开运行的app"                            
     activate                           
	 repeat with website in websiteList                          
	        open location website                                          
	end repeat                                                  
end tell                      
