# relx-pbis-wrapper
FPM Build Command:
 fpm -s dir -t rpm -n relx-pbis-wrapper --after-install usr/local/relx-pbis-open/scripts/set_chkconfig -x .git -v 1.0.4 --description "RELX PBIS Wrapper for NL Domain Join" .
Including the dot at the End
