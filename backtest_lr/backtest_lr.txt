# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Fast exact finite-sample back-testing for Value-at-Risk (VaR) models Use backtest_lr and backtest_all (ExactVaRTest) With (In) R Software
install.packages("ExactVaRTest")
library("ExactVaRTest")
# Estimation Fast exact finite-sample back-testing for Value-at-Risk (VaR) models Use backtest_lr and backtest_all (ExactVaRTest) With (In) R Software
backtest_lr = read.csv("https://raw.githubusercontent.com/timbulwidodostp/backtest_lr/main/backtest_lr/backtest_lr.csv", sep = ";")
x <- backtest_lr$x
backtest_lr <- backtest_lr(x, alpha = 0.05, type = "cc")
backtest_lr
backtest_all <- backtest_all(x, alpha = 0.02)
backtest_all
# Fast exact finite-sample back-testing for Value-at-Risk (VaR) models Use backtest_lr and backtest_all (ExactVaRTest) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished