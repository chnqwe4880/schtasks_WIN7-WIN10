# schtasks_WIN7-WIN10
  
# schtasks /Create  /TN cmd /TR C:\Windows\System32\cmd.exe /SC once /ST 18:53  
  
用法schtasks /create /tn [任务名称] /tr [路径] /sc once /st [时间]    PS： once为一次性

立即运行的方法 把任务时间设置成过去式 schtasks /run /tn [任务名称]
