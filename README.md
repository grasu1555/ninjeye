# <a href="https://m2protect.net/"><img src="https://m2protect.net/assets/img/brand/white.png" /></a>
<ul>
  <li>:rocket: v138
    <ul>
      <li>
          :sparkler:  Fixed errors that occurred in Windows 7
      </li>
      <li>
          :wrench:  Reworked the exported GetUniqueHash() function
            <ul>
              :information_source: Changed to 'void __cdecl ex_GetUniqueHash(char* ex_uniqueHash);'. You may allocate a 32 + 1 bytes long char array on heap in order to get the requested ex_uniqueHash. Do not forget to free the memory after use.
            </ul>
      </li>
      <li>
          :white_check_mark:  Added a new check for the internet connection
            <ul>
              :information_source: In the past, users could start the client with no internet connection which resulted in the situation that protection was disabled. This can no longer be done. An error message is thrown if there is no internet connection at run-time.
            </ul>
      </li>
      <li>
          :gun:  Fixed the latest versions of M2Bob<br>
      </li>
      <li>
          :bomb:  Fixed python code injections exploit with the help of mss32.dll
            <ul>
              :information_source: At the run-time, mss32.dll executes any file it finds in the client folder with the following extensions .mix, .asi, .flt, .m3d. User-added files are being detected from now on.
            </ul>
      </li>
      <li>
        <a href="https://www.virustotal.com/gui/file/ce6ea70ca2c198e0cd051313f16d7211691a6cee81eecc8685f1c3868bd60c24"> 
          :robot:  VirusTotal (false-positives due to encryptions used)
        </a>
      </li>
    </ul>
  </li>
</ul>
