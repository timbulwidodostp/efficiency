# Olah Data Semarang 
# WhatsApp : +6285227746673 
# IG : @olahdatasemarang_ 
# Slope, R2 and Efficiency (E) statistics and standard curves Use efficiency (rtpcr) With (In) R Software
install.packages("rtpcr") 
library("rtpcr")
efficiency = read.csv("https://raw.githubusercontent.com/timbulwidodostp/efficiency/main/efficiency/efficiency.csv",sep = ";") 
# Estimation Slope, R2 and Efficiency (E) statistics and standard curves Use efficiency (rtpcr) With (In) R Software 
dilutions <- efficiency$dilutions
C2H2.26 <- efficiency$C2H2.26
C2H2.01 <- efficiency$C2H2.01
GAPDH <- efficiency$GAPDH
efficiency <- data.frame(dilutions, C2H2.26, C2H2.01, GAPDH) 
efficiency(efficiency)
# Slope, R2 and Efficiency (E) statistics and standard curves Use efficiency (rtpcr) With (In) R Software
# Olah Data Semarang 
# WhatsApp : +6285227746673 
# IG : @olahdatasemarang_ 
# Finished