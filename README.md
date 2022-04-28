# replace-blank-with-end-of-string
; If you want data from beginning then replace blank start with beginning of string     $sStart = $sStart ? "\Q" &amp; $sStart &amp; "\E" : "\A"      ; If you want data from a start to an end then replace blank with end of string     $sEnd = $sEnd ? "(?=\Q" &amp; $sEnd &amp; "\E)" : "\z"
