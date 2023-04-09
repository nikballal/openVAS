# Vulnerability Assessment using OpenVAS/Greenbone Vulnerability Scanner

 ### 1. On Kali linux, host IP - 192.168.0.222, check for the machines available on the host using 'nmap' command on the CLI and output the into a target file Target_List.txt

 ### 2. Using vim command, edit the text file to only contain the IPs on the host, delete remaining data and save the text file.
   <img width="382" alt="IPs" src="https://user-images.githubusercontent.com/89782464/230750068-faa69139-7be4-483f-9416-ace729976944.PNG">

### 3. Open browser, enter the loopback address (localhost) on the browser to navigate to OpenVAS GUI

### 4. Navigate to Configuration. Create a new target, and upload the text file. Exclude the host IP

### 5. Navigate to Scan, perform new scan and check results.
   <img width="382" alt="vul-scan" src="https://user-images.githubusercontent.com/89782464/230750072-a1d48fdc-7bbe-48a3-97d4-497eb07aba96.PNG">
   
### 6. Download the report.

### 7. Rename the report using 'mv' command to 'corporate_scan.txt'
  <img width="387" alt="corporate_scan" src="https://user-images.githubusercontent.com/89782464/230750077-05d59383-7562-47ca-93ef-8880c32a1d61.PNG">

### 8. Start the python3 simple http server on the linux CLI to access the txt file corporate_scan.txt

### 9. Move over to user pc - windows machine 'on the same subnet'. Go to browser. Enter the host IP on port 8080, navigate to corporate_scan.txt

### 10. Downloaded report appears as webpage containing the scanned data

### 11. Document as vulnerability scan report using OpenOffice save it as PDF.
