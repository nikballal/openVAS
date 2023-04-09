# OpenVAS
Vulnerability Assessment using OpenVAS/Greenbone Vulnerability Scanner

 1. On Kali linux, host IP - 192.168.0.222, check for the machines available on the host using 'nmap' command on the CLI and output the into a target file
Target_List.txt

 2. Using vim command, edit the text file to only contain the IPs on the host, delete remaining data and save the text file.
         <img width="382" alt="IPs" src="https://user-images.githubusercontent.com/89782464/230749969-e67a4761-691a-4cab-b77f-228240203df3.PNG">

3. Open browser, enter the loopback address on the browser to navigate to OpenVAS GUI

4. Navigate to Configuration. Create a new target, and upload the text file. Exclude the host IP

5. Navigate to Scan, perform new scan and check results.
         <img width="471" alt="vul-scan" src="https://user-images.githubusercontent.com/89782464/230749977-2ed7af24-00a4-4288-b94d-5063cc726ff5.PNG">

6. Download the report.

7. Rename the report using 'mv' command to corporate_scan.txt'
          <img width="387" alt="corporate_scan" src="https://user-images.githubusercontent.com/89782464/230749982-0454780a-b732-447d-b9e0-bee165c1b148.PNG">

8. Start the python3 simple server

9. Move over to windows machine. Go to browser. Enter the host IP on port 8080

10. Downloaded report appears as webpage containing the scanned data

11. Use this data to fill out a vulnerability report using openoffice and save it as PDF
