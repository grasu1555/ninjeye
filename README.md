# <a href="https://m2protect.net/"><img src="https://m2protect.net/assets/img/brand/white.png" /></a>
<ul>
  <li>:rocket: v138
    <ul>
      <li>
          :white_check_mark:  Added a new check for the internet connection
            <ul>
              :information_source: In the past, users could start the client with no internet connection which resulted in the situation that protection was disabled. This can no longer be done. An exception is thrown if there is no internet connection at run-time.
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
        <a href="https://www.virustotal.com/gui/file/2c76b3ff49644d0a27e29749890f1afd861ea155bf51846e4b4eee6c84f25b1a"> 
          :robot:  VirusTotal (false-positives due to encryptions used)
        </a>
      </li>
    </ul>
  </li>
</ul>
