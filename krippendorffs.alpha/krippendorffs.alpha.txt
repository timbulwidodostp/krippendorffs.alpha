# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Compute a confidence interval for Krippendorff's Alpha Use krippendorffs.alpha (krippendorffsalpha) With (In) R Software
install.packages("krippendorffsalpha")
library("krippendorffsalpha")
# Estimation Compute a confidence interval for Krippendorff's Alpha Use krippendorffs.alpha (krippendorffsalpha) With (In) R Software
krippendorffs.alpha = read.csv("https://raw.githubusercontent.com/timbulwidodostp/krippendorffs.alpha/main/krippendorffs.alpha/krippendorffs.alpha.csv",sep = ";")
krippendorffs.alpha = as.matrix(krippendorffs.alpha[1:100, ])
krippendorffs.alpha = krippendorffs.alpha(krippendorffs.alpha, level = "ratio", method = "customary", confint = TRUE, control = list(bootit = 1000, parallel = FALSE))
summary(krippendorffs.alpha)
# Compute a confidence interval for Krippendorff's Alpha Use krippendorffs.alpha (krippendorffsalpha) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished