# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Common Correlated Effects estimators Use pmg And pcce (In) With R Software
# Common Correlated Effects Mean Groups Use pmg And pcce (In) With R Software
install.packages("plm")
library("plm")
pmg = read.csv("https://raw.githubusercontent.com/timbulwidodostp/pmg/main/pmg/pmg.csv",sep = ";")
# Estimate Common Correlated Effects estimators Use pmg And pcce (In) With R Software
pmg<-pmg(Dependen~Independen_1+Independen_2+Independen_3+Independen_4,data=pmg,model="cmg")
summary(pmg)
pmg = read.csv("https://raw.githubusercontent.com/timbulwidodostp/pmg/main/pmg/pmg.csv",sep = ";")
pcce<-pcce(Dependen~Independen_1+Independen_2+Independen_3+Independen_4,data=pmg,model="mg")
summary(pcce)
# Common Correlated Effects estimators Use pmg And pcce (In) With R Software
# Common Correlated Effects Mean Groups Use pmg And pcce (In) With R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished
