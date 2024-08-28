<h4>24hrs Insecure Environment </h4>
We are going to be tracking the BEFORE SECURING ENVIRONMENT.
<img src="https://github.com/user-attachments/assets/a4704e91-40b4-4946-a09d-1154702c15c1" height="80%" width="80%" />


<p>
  <img src="https://github.com/user-attachments/assets/093e0904-1199-4d5f-aeba-3ea824af16b8" height="80%" width="80%" />
</p>
<h5>Start Time and Stop Time</h5>
<p> this generates a single-row and a single column named X. the range starts and ends with 1. The first code is just to set up the table but the 2nd code creates two new columns StartTime and StopTime in the output.
 </p>

  <p>
     <img src="https://github.com/user-attachments/assets/ea620233-45d3-4748-b8ca-591bf8f132f0" height="80%" width="80%" />
   <h5>Security Events (Windows VMs)</h5>
    <p>
counting the number of security events that happened in the last 24hrs.</p>
  </p>

  
<p> <img src="https://github.com/user-attachments/assets/879cc7f3-2c72-4bd3-8775-daab531611bc" height="80%" width="80%" />
   
</p>
<h5>Syslog (Linux VMs)</h5>
<p>the number of Syslog msgs generated in the last 24 hours</p>


 <p>
  <img src="https://github.com/user-attachments/assets/ced9bfbf-7e29-447e-a9be-0322dcf80497" height="80%" width="80%" />

 </p>
    <h5>SecurityAlert (Microsoft Defender for Cloud)</h5>
    <p>the count of security alerts generated in the last 24 hours that do not start with "CUSTOM" or "TEST" in their DisplayName.</p>

    
 <p>
    <img src="https://github.com/user-attachments/assets/94581a47-31a6-4974-b026-041b4d7d66c2" height="80%" width="80%" /> </p>
   <h5>Security Incident (Sentinel Incidents)</h5>
    <p>
the volume of security incidents reported within the last 24 hours</p>
  </p>


<p>
    <img src="https://github.com/user-attachments/assets/fd1030b5-b7d6-46bf-a3c4-a44af3eca1e9" height="80%" width="80%" /> </p>
   <h5>NSG Inbound Malicious Flows Allowed</h5>
    <p>
allowed malicious network flows recorded in the last 24 hours.
</p>
  </p>


<p>
    <img src="https://github.com/user-attachments/assets/57b3aff3-c23c-4926-aec9-bd52f7b1c076" height="80%" width="80%" /> </p>
   <h5> NSG Inbound Malicious Flows Blocked</h5>
    <p>
the count of malicious network flows that were denied in the last 24 hours.
</p>
  </p>


  <br />

______________________________________________________________________________________________________________________


<br />

<h4>Capturing Analytics </h4>
<p> RECAP: I created these maps in <a href="https://github.com/florenceajadi/world-maps-construction">World Map Constructions</a>. This is capturing the maps in the last 24hrs. 
</p>
<p>
   <img src="https://github.com/user-attachments/assets/ec512d7a-8f87-4710-81fd-402f6c22d895" height="80%" width="80%" /> 
   <p>
   This is capturing NSG-Malicious-Flows-Allowed in the last 24hrs. As you can see, besdies Odesa being the most malicious, but OTHERS as well.
   </p>
</p>


<p>
<img src="https://github.com/user-attachments/assets/014f6c69-be9e-4a39-8a7d-5bd8e89b8717" height="80%" width="80%" /> 
</p>
<p>with windows-rdp-auth-fail, there are over 3.37K in the U.S of failed auth.</p>


