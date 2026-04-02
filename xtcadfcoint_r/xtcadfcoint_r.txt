# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Panel CADF cointegration test with structural breaks and cross-section dependence Use xtcadfcoint With (in) R Software
install.packages("remotes")
remotes::install_github("muhammedalkhalaf/xtcadfcoint")
library("xtcadfcoint")
# Estimation Panel CADF cointegration test with structural breaks and cross-section dependence Use xtcadfcoint With (in) R Software
xtcadfcoint_r = read.csv("https://raw.githubusercontent.com/timbulwidodostp/xtcadfcoint_r/main/xtcadfcoint_r/xtcadfcoint_r.csv",sep = ";")
xtcadfcoint <- xtcadfcoint(xtcadfcoint ~ xtcadfcoint_, data = xtcadfcoint_r, index = c("state", "year"), model = 1, breaks = 0)
xtcadfcoint
xtcadfcoint_ <- xtcadfcoint(xtcadfcoint ~ xtcadfcoint_, data = xtcadfcoint_r, index = c("state", "year"), model = 3, breaks = 1)
xtcadfcoint_
# Panel CADF cointegration test with structural breaks and cross-section dependence Use xtcadfcoint With (in) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished