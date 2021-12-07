# <a href="https://ninjeye.net/"><img src="https://ninjeye.net/assets/img/brand/white.png" /></a>
<ul>
  <li>:rocket: v141
    <ul>
      <li>
        :link:  M2Protect is slowly translating into <b>NinjEye</b>
            <ul>
              :information_source: The <b>NinjEye</b> directory must include <b>ninjeye.bmp</b> and <b>ninjeye.dll</b>. The old M2Protect directory will be automatically removed.
            </ul>
      </li>
      <li>
        :x: <b>REMOVED</b>  <strike><b>The application can be opened only via its launcher. Any other openers are disabled.</b>
            <ul>
              :information_source: Exception for autopatcher: The application can be opened via patcher only if patcher <b>REMAINS OPEN</b> after opening the game and <b>NOT</b> closing itself.
            </ul></strike>
      </li>
      <li>
          :wrench:  Reworked the exported m4in() function
            <ul>
              :information_source: Changed to 'void __cdecl m4in(DWORD *arg7, DWORD *arg8, std::vector< DWORD > *dwThIDs, DWORD licenseKey);'. Removed the first parameter.
            </ul>
      </li>
      <li>
        <a href="https://www.virustotal.com/gui/file/939e69dc4a3a0e67af5ee021090031dc71d15b8f8a361c11c8b5cf2d4578830d"> 
          :robot:  VirusTotal
        </a>
      </li>
    </ul>
  </li>
  <li>:rocket: v140
    <ul>
      <li>
          :mega:  Welcome the <a href="https://ninjeye.net/">NinjEye.net</a>
            <ul>
              :information_source: M2Protect.net has been a wonderul project for 3 1/2 years. It's time for enhancement.
            </ul>
      </li>
      <li>
        :cupid:  <b>The application can be opened only via its launcher. Any other openers are disabled.</b>
            <ul>
              :information_source: Exception for autopatcher: The application can be opened via patcher only if patcher <b>REMAINS OPEN</b> after opening the game and <b>NOT</b> closing itself.
            </ul>
      </li>
      <li>
        :postal_horn:  Fixed <b><i>all hacks</i></b> that worked on versions before<br>
      </li>
      <li>
          :airplane:  Fixed Reksati's Macro<br>
      </li>
      <li>
          :100:  Fixed some little bugs<br>
      </li>
      <li>
          :x:  Removed EterX checks<br>
      </li>
      <li>
           :love_letter:  Added email address and information to MessageBox errors
      </li>
      <li>
          :laughing:  A lot of other changes and improvements that I can not write here because cuckoos are :eyes:<br>
      </li>
    </ul>
  </li>
  <li>:rocket: v139
    <ul>
      <li>
          :beer:  Fixed a trick that could bypass the protection
      </li>
      <li>
          :wrench:  Reworked the exported m4in() function
            <ul>
              :information_source: Changed to 'void __cdecl m4in(bool enabled, DWORD *arg7, DWORD *arg8, std::vector< DWORD > *dwThIDs, DWORD licenseKey);'. First parameter must be true.
            </ul>
      </li>
      <li>
          :gun:  Fixed the latest version of SpankTeamMod<br>
      </li>
      <li>
          :roller_coaster:  Upgraded to OpenSSL 3.0 and Curl 7.80
      </li>
    </ul>
  </li>
  <li>:rocket: v138
    <ul>
      <li>
          :sparkler:  Fixed errors that occurred in Windows 7
      </li>
      <li>
          :wrench:  Reworked the exported GetUniqueHash() function
            <ul>
              :information_source: Changed to 'void __cdecl ex_GetUniqueHash(char* ex_uniqueHash);'. You may allocate a 32 + 1 bytes long char array in order to get the requested ex_uniqueHash.
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
    </ul>
  </li>
</ul>
