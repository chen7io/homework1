'201809_data'<-read.csv("/Users/jen/Downloads/201809_data.xlsx", header=T, sep=",")
'201811_data'<-read.csv("/Users/jen/Downloads/201811_data.xlsx", header=T, sep=",")
'201812_data'<-read.csv("/Users/jen/Downloads/201812_data.xlsx", header=T, sep=",")
library(methods)
library(ggplot2)
'201801_data'<-read.csv("/Users/jen/Downloads/201801_data.xlsx", header=T, sep=",")
'201802_data'<-read.csv("/Users/jen/Downloads/201802_data.xlsx", header=T, sep=",")
'201803_data'<-read.csv("/Users/jen/Downloads/201803_data.xlsx", header=T, sep=",")
'201804_data'<-read.csv("/Users/jen/Downloads/201804_data.xlsx", header=T, sep=",")
'201805_data'<-read.csv("/Users/jen/Downloads/201805_data.xlsx", header=T, sep=",")
'201806_data'<-read.csv("/Users/jen/Downloads/201806_data.xlsx", header=T, sep=",")
'201807_data'<-read.csv("/Users/jen/Downloads/201807_data.xlsx", header=T, sep=",")
'201808_data'<-read.csv("/Users/jen/Downloads/201808_data.xlsx", header=T, sep=",")
'201809_data'<-read.csv("/Users/jen/Downloads/201809_data.xlsx", header=T, sep=",")
'201810_data'<-read.csv("/Users/jen/Downloads/201810_data.xlsx", header=T, sep=",")
'201811_data'<-read.csv("/Users/jen/Downloads/201811_data.xlsx", header=T, sep=",")
'201812_data'<-read.csv("/Users/jen/Downloads/201812_data.xlsx", header=T, sep=",")
'201901_data'<-read.csv("/Users/jen/Downloads/201901_data.xlsx", header=T, sep=",")

#1.台北市長聲量比較圖
#初始化變數
counta<-c(rep.int(x=0,times = 12))
countb<-c(rep.int(x=0,times = 12))
countc<-c(rep.int(x=0,times = 12))
#尋找2018中提及柯文哲的文章內容
for (i in grep("柯",`201801_data`$Message)) {
  counta[1]=counta[1]+1
}
for (i in grep("柯",`201802_data`$Message)) {
  counta[2]=counta[2]+1
}
for (i in grep("柯",`201803_data`$Message)) {
  counta[3]=counta[3]+1
}
for (i in grep("柯",`201804_data`$Message)) {
  counta[4]=counta[4]+1
}
for (i in grep("柯",`201805_data`$Message)) {
  counta[5]=counta[5]+1
}
for (i in grep("柯",`201806_data`$Message)) {
  counta[6]=counta[6]+1
}
for (i in grep("柯",`201807_data`$Message)) {
  counta[7]=counta[7]+1
}
for (i in grep("柯",`201808_data`$Message)) {
  counta[8]=counta[8]+1
}
for (i in grep("柯",`201809_data`$Message)) {
  counta[9]=counta[9]+1
}
for (i in grep("柯",`201810_data`$Message)) {
  counta[10]=counta[10]+1
}
for (i in grep("柯",`201811_data`$Message)) {
  counta[11]=counta[11]+1
}
for (i in grep("柯",`201812_data`$Message)) {
  counta[12]=counta[12]+1
}
for (i in grep("柯",`201901_data`$Message)) {
  counta[13]=counta[13]+1
}
kp<-counta
kp
#尋找2018中提及姚文智的內容
for (i in grep("姚",`201801_data`$Message)) {
  countb[1]=countb[1]+1
}
for (i in grep("姚",`201802_data`$Message)) {
  countb[2]=countb[2]+1
}
for (i in grep("姚",`201803_data`$Message)) {
  countb[3]=countb[3]+1
}
for (i in grep("姚",`201804_data`$Message)) {
  countb[4]=countb[4]+1
}
for (i in grep("姚",`201805_data`$Message)) {
  countb[5]=countb[5]+1
}
for (i in grep("姚",`201806_data`$Message)) {
  countb[6]=countb[6]+1
}
for (i in grep("姚",`201807_data`$Message)) {
  countb[7]=countb[7]+1
}
for (i in grep("姚",`201808_data`$Message)) {
  countb[8]=countb[8]+1
}
for (i in grep("姚",`201809_data`$Message)) {
  countb[9]=countb[9]+1
}
for (i in grep("姚",`201810_data`$Message)) {
  countb[10]=countb[10]+1
}
for (i in grep("姚",`201811_data`$Message)) {
  countb[11]=countb[11]+1
}
for (i in grep("姚",`201812_data`$Message)) {
  countb[12]=countb[12]+1
}
for (i in grep("姚",`201901_data`$Message)) {
  countb[13]=countb[13]+1
}
#尋找2018中提及丁守中的內容
for (i in grep("丁",`201801_data`$Message)) {
  countc[1]=countc[1]+1
}

for (i in grep("丁",`201802_data`$Message)) {
  countc[2]=countc[2]+1
}
for (i in grep("丁",`201803_data`$Message)) {
  countc[3]=countc[3]+1
}
for (i in grep("丁",`201804_data`$Message)) {
  countc[4]=countc[4]+1
}
for (i in grep("丁",`201805_data`$Message)) {
  countc[5]=countc[5]+1
}
for (i in grep("丁",`201806_data`$Message)) {
  countc[6]=countc[6]+1
}
for (i in grep("丁",`201807_data`$Message)) {
  countc[7]=countc[7]+1
}
for (i in grep("丁",`201808_data`$Message)) {
  countc[8]=countc[8]+1
}
for (i in grep("丁",`201809_data`$Message)) {
  countc[9]=countc[9]+1
}
for (i in grep("丁",`201810_data`$Message)) {
  countc[10]=countc[10]+1
}
for (i in grep("丁",`201811_data`$Message)) {
  countc[11]=countc[11]+1
}
for (i in grep("丁",`201812_data`$Message)) {
  countc[12]=countc[12]+1
}
for (i in grep("丁",`201901_data`$Message)) {
  countc[13]=countc[13]+1
}
dd<-countc
uu<-countb

Month<-c(rep.int(1:13,3))
tot<-c(kp,uu,dd)
Candidate<-c(rep("kp",13),rep("uu",13),rep("dd",13))
#給定一個dataframe
testfor1<- data.frame( 
  Month,Candidate,tot
) 
print(testfor1) 
par(family = "PingFangTC-Medium") #嘗試指定中文字型（但失敗）
system("defaults write org.R-project.R force.LANG zh_TW.UTF-8")#嘗試使用中文第二次，失敗第二次
#畫折線圖，使用ggplot2 package，放棄使用中文
ggplot(testfor1,aes(x=Month,y=tot,color=Candidate,group=Candidate))+geom_line()+ggtitle("Taipei")+xlab("Month")+ylab("count")+geom_point(size = 1)+
 xlim(1,12)

##韓國瑜和陳其邁在大選期間的讚數和貼文數量比較
sum_han=0;sum_ccm=0;sum_han2=0;sum_ccm2=0
x1<-subset(`201801_data`,Page_Name=="韓國瑜",select =c("LIKE_COUNT","Comment_Count"))
x1<-rbind(x1,subset(`201802_data`,Page_Name=="韓國瑜",select =c("LIKE_COUNT","Comment_Count")),subset(`201803_data`,Page_Name=="韓國瑜",select =c("LIKE_COUNT","Comment_Count")),subset(`201804_data`,Page_Name=="韓國瑜",select =c("LIKE_COUNT","Comment_Count")),
      subset(`201805_data`,Page_Name=="韓國瑜",select =c("LIKE_COUNT","Comment_Count")),subset(`201806_data`,Page_Name=="韓國瑜",select =c("LIKE_COUNT","Comment_Count")),subset(`201807_data`,Page_Name=="韓國瑜",select =c("LIKE_COUNT","Comment_Count")),subset(`201808_data`,Page_Name=="韓國瑜",select =c("LIKE_COUNT","Comment_Count")),subset(`201809_data`,Page_Name=="韓國瑜",select =c("LIKE_COUNT","Comment_Count")),
      subset(`201810_data`,Page_Name=="韓國瑜",select =c("LIKE_COUNT","Comment_Count")),subset(`201811_data`,Page_Name=="韓國瑜",select =c("LIKE_COUNT","Comment_Count")),subset(`201812_data`,Page_Name=="韓國瑜",select =c("LIKE_COUNT","Comment_Count")),subset(`201901_data`,Page_Name=="韓國瑜",select =c("LIKE_COUNT","Comment_Count")))
sum_han<-sum(as.numeric(x1$LIKE_COUNT))
sum_han2<-sum(as.numeric(x1$Comment_Count))
x2<-subset(`201801_data`,Page_Name=="陳其邁 Chen Chi-Mai",select =c("LIKE_COUNT","Comment_Count"))
x2<-rbind(x2,subset(`201802_data`,Page_Name=="陳其邁 Chen Chi-Mai",select =c("LIKE_COUNT","Comment_Count")),subset(`201802_data`,Page_Name=="陳其邁 Chen Chi-Mai",select =c("LIKE_COUNT","Comment_Count")),subset(`201803_data`,Page_Name=="陳其邁 Chen Chi-Mai",select =c("LIKE_COUNT","Comment_Count")),subset(`201804_data`,Page_Name=="陳其邁 Chen Chi-Mai",select =c("LIKE_COUNT","Comment_Count"))
          ,subset(`201805_data`,Page_Name=="陳其邁 Chen Chi-Mai",select =c("LIKE_COUNT","Comment_Count")),subset(`201806_data`,Page_Name=="陳其邁 Chen Chi-Mai",select =c("LIKE_COUNT","Comment_Count")),subset(`201807_data`,Page_Name=="陳其邁 Chen Chi-Mai",select =c("LIKE_COUNT","Comment_Count")),subset(`201808_data`,Page_Name=="陳其邁 Chen Chi-Mai",select =c("LIKE_COUNT","Comment_Count")),subset(`201809_data`,Page_Name=="陳其邁 Chen Chi-Mai",select =c("LIKE_COUNT","Comment_Count"))
          ,subset(`201810_data`,Page_Name=="陳其邁 Chen Chi-Mai",select =c("LIKE_COUNT","Comment_Count")),subset(`201811_data`,Page_Name=="陳其邁 Chen Chi-Mai",select =c("LIKE_COUNT","Comment_Count")),subset(`201812_data`,Page_Name=="陳其邁 Chen Chi-Mai",select =c("LIKE_COUNT","Comment_Count")),subset(`201901_data`,Page_Name=="陳其邁 Chen Chi-Mai",select =c("LIKE_COUNT","Comment_Count")))
sum_ccm<-sum(as.numeric(x2$LIKE_COUNT))
sum_ccm2<-sum(as.numeric(x2$Comment_Count))
x1['person']='han'
x2['person']='ccm'
new_data1<-matrix(c(sum_ccm,sum_ccm2,sum_han,sum_han2),nrow=2,ncol=2,byrow = TRUE)
new_data1<-prop.table(new_data1)
rownames(new_data1)<-c("han","ccm")
colnames(new_data1)<-c("like","comment")
# Create the input vectors.
colors = c("orange","brown")
people<-c("han","ccm")
types<-c("comment","like")
# Create the bar chart
barplot(new_data1,main="comparison between Kaoshiung",names.arg = people,col = colors,ylab = "count")
# Add the legend to the chart
legend("topright", types, cex = 0.8, fill = colors)

##韓國瑜的表情貼趨勢
s1<-sum(`201801_data`$LIKE_COUNT[which(grepl("^韓國瑜$",`201801_data`$Page_Name))])
s2<-sum(`201802_data`$LIKE_COUNT[which(grepl("^韓國瑜$",`201802_data`$Page_Name))])
s3<-sum(`201803_data`$LIKE_COUNT[which(grepl("^韓國瑜$",`201803_data`$Page_Name))])
s3<-as.numeric(`201803_data`$LIKE_COUNT[which(grepl("^韓國瑜$",`201803_data`$Page_Name))])
s3<-sum(s3)
s4<-sum(`201804_data`$LIKE_COUNT[which(grepl("^韓國瑜$",`201804_data`$Page_Name))])
s5<-as.numeric(`201805_data`$LIKE_COUNT[which(grepl("^韓國瑜$",`201805_data`$Page_Name))])
s5<-sum(s5)
s6<-sum(`201806_data`$LIKE_COUNT[which(grepl("^韓國瑜$",`201806_data`$Page_Name))])
s7<-sum(`201807_data`$LIKE_COUNT[which(grepl("^韓國瑜$",`201807_data`$Page_Name))])
s8<-sum(`201808_data`$LIKE_COUNT[which(grepl("^韓國瑜$",`201808_data`$Page_Name))])
s9<-as.numeric(`201809_data`$LIKE_COUNT[which(grepl("^韓國瑜$",`201809_data`$Page_Name))])
s9<-sum(s9)
s10<-sum(`201810_data`$LIKE_COUNT[which(grepl("^韓國瑜$",`201810_data`$Page_Name))])
s11<-sum(`201811_data`$LIKE_COUNT[which(grepl("^韓國瑜$",`201811_data`$Page_Name))])
s12<-as.numeric(`201812_data`$LIKE_COUNT[which(grepl("^韓國瑜$",`201812_data`$Page_Name))])
s12<-sum(s12)
s13<-sum(`201901_data`$LIKE_COUNT[which(grepl("^韓國瑜$",`201901_data`$Page_Name))])

w1<-sum(`201801_data`$WOW_COUNT[which(grepl("^韓國瑜$",`201801_data`$Page_Name))])
w2<-sum(`201802_data`$WOW_COUNT[which(grepl("^韓國瑜$",`201802_data`$Page_Name))])
w3<-as.numeric(`201803_data`$WOW_COUNT[which(grepl("^韓國瑜$",`201803_data`$Page_Name))])
w3<-sum(w3)
w4<-sum(`201804_data`$WOW_COUNT[which(grepl("^韓國瑜$",`201804_data`$Page_Name))])
w5<-as.numeric(`201805_data`$WOW_COUNT[which(grepl("^韓國瑜$",`201805_data`$Page_Name))])
w5<-sum(w5)
w6<-sum(`201806_data`$WOW_COUNT[which(grepl("^韓國瑜$",`201806_data`$Page_Name))])
w7<-sum(`201807_data`$WOW_COUNT[which(grepl("^韓國瑜$",`201807_data`$Page_Name))])
w8<-sum(`201808_data`$WOW_COUNT[which(grepl("^韓國瑜$",`201808_data`$Page_Name))])
w9<-as.numeric(`201809_data`$WOW_COUNT[which(grepl("^韓國瑜$",`201809_data`$Page_Name))])
w9<-sum(w9)
w10<-sum(`201810_data`$WOW_COUNT[which(grepl("^韓國瑜$",`201810_data`$Page_Name))])
w11<-sum(`201811_data`$WOW_COUNT[which(grepl("^韓國瑜$",`201811_data`$Page_Name))])
w12<-as.numeric(`201812_data`$WOW_COUNT[which(grepl("^韓國瑜$",`201812_data`$Page_Name))])
w12<-sum(w12)
w13<-0

l1<-sum(`201801_data`$LOVE_COUNT[which(grepl("^韓國瑜$",`201801_data`$Page_Name))])
l2<-sum(`201802_data`$LOVE_COUNT[which(grepl("^韓國瑜$",`201802_data`$Page_Name))])
l3<-as.numeric(`201803_data`$LOVE_COUNT[which(grepl("^韓國瑜$",`201803_data`$Page_Name))])
l3<-sum(w3)
l4<-sum(`201804_data`$LOVE_COUNT[which(grepl("^韓國瑜$",`201804_data`$Page_Name))])
l5<-as.numeric(`201805_data`$LOVE_COUNT[which(grepl("^韓國瑜$",`201805_data`$Page_Name))])
l5<-sum(l5)
l6<-sum(`201806_data`$LOVE_COUNT[which(grepl("^韓國瑜$",`201806_data`$Page_Name))])
l7<-sum(`201807_data`$LOVE_COUNT[which(grepl("^韓國瑜$",`201807_data`$Page_Name))])
l8<-sum(`201808_data`$LOVE_COUNT[which(grepl("^韓國瑜$",`201808_data`$Page_Name))])
l9<-as.numeric(`201809_data`$WOW_COUNT[which(grepl("^韓國瑜$",`201809_data`$Page_Name))])
l9<-sum(l9)
l10<-sum(`201810_data`$LOVE_COUNT[which(grepl("^韓國瑜$",`201810_data`$Page_Name))])
l11<-sum(`201811_data`$LOVE_COUNT[which(grepl("^韓國瑜$",`201811_data`$Page_Name))])
l12<-as.numeric(`201812_data`$LOVE_COUNT[which(grepl("^韓國瑜$",`201812_data`$Page_Name))])
l12<-sum(l12)
l13<-0

like_han<-data.frame(month=c(1:12,13),count=c(s1,s2,s3,s4,s5,s6,s7,s8,s9,s10,s11,s12,s13,w1,w2,w3,w4,w5,w6,w7,w8,w9,w10,w11,w12,w13,l1,l2,l3,l4,l5,l6,l7,l8,l9,l10,l11,l12,l13),
                     types=c('like','like','like','like','like','like','like','like','like','like','like','like','like','wow','wow','wow','wow','wow','wow','wow','wow','wow','wow','wow','wow','wow','love','love','love','love','love','love','love','love','love','love','love','love','love'))

p1 <- ggplot(like_han, aes(x =month, y =count,colour=types))+ geom_line()+ scale_colour_brewer(palette = "Set2")
p1

##陳其邁的表情圖趨勢
s1<-sum(`201801_data`$LIKE_COUNT[which(grepl("^陳其邁 Chen Chi-Mai$",`201801_data`$Page_Name))])
s2<-sum(`201802_data`$LIKE_COUNT[which(grepl("^陳其邁 Chen Chi-Mai$",`201802_data`$Page_Name))])
s3<-sum(`201803_data`$LIKE_COUNT[which(grepl("^陳其邁 Chen Chi-Mai$",`201803_data`$Page_Name))])
s3<-as.numeric(`201803_data`$LIKE_COUNT[which(grepl("^陳其邁 Chen Chi-Mai$",`201803_data`$Page_Name))])
s3<-sum(s3)
s4<-sum(`201804_data`$LIKE_COUNT[which(grepl("^陳其邁 Chen Chi-Mai$",`201804_data`$Page_Name))])
s5<-as.numeric(`201805_data`$LIKE_COUNT[which(grepl("^陳其邁 Chen Chi-Mai$",`201805_data`$Page_Name))])
s5<-sum(s5)
s6<-sum(`201806_data`$LIKE_COUNT[which(grepl("^陳其邁 Chen Chi-Mai$",`201806_data`$Page_Name))])
s7<-sum(`201807_data`$LIKE_COUNT[which(grepl("^陳其邁 Chen Chi-Mai$",`201807_data`$Page_Name))])
s8<-sum(`201808_data`$LIKE_COUNT[which(grepl("^陳其邁 Chen Chi-Mai$",`201808_data`$Page_Name))])
s9<-as.numeric(`201809_data`$LIKE_COUNT[which(grepl("^陳其邁 Chen Chi-Mai$",`201809_data`$Page_Name))])
s9<-sum(s9)
s10<-sum(`201810_data`$LIKE_COUNT[which(grepl("^陳其邁 Chen Chi-Mai$",`201810_data`$Page_Name))])
s11<-sum(`201811_data`$LIKE_COUNT[which(grepl("^陳其邁 Chen Chi-Mai$",`201811_data`$Page_Name))])
s12<-as.numeric(`201812_data`$LIKE_COUNT[which(grepl("^陳其邁 Chen Chi-Mai$",`201812_data`$Page_Name))])
s12<-sum(s12)
s13<-sum(`201901_data`$LIKE_COUNT[which(grepl("^陳其邁 Chen Chi-Mai$",`201901_data`$Page_Name))])

w1<-sum(`201801_data`$WOW_COUNT[which(grepl("^陳其邁 Chen Chi-Mai$",`201801_data`$Page_Name))])
w2<-sum(`201802_data`$WOW_COUNT[which(grepl("^陳其邁 Chen Chi-Mai$",`201802_data`$Page_Name))])
w3<-as.numeric(`201803_data`$WOW_COUNT[which(grepl("^陳其邁 Chen Chi-Mai$",`201803_data`$Page_Name))])
w3<-sum(w3)
w4<-sum(`201804_data`$WOW_COUNT[which(grepl("^陳其邁 Chen Chi-Mai$",`201804_data`$Page_Name))])
w5<-as.numeric(`201805_data`$WOW_COUNT[which(grepl("^陳其邁 Chen Chi-Mai$",`201805_data`$Page_Name))])
w5<-sum(w5)
w6<-sum(`201806_data`$WOW_COUNT[which(grepl("^陳其邁 Chen Chi-Mai$",`201806_data`$Page_Name))])
w7<-sum(`201807_data`$WOW_COUNT[which(grepl("^陳其邁 Chen Chi-Mai$",`201807_data`$Page_Name))])
w8<-sum(`201808_data`$WOW_COUNT[which(grepl("^陳其邁 Chen Chi-Mai$",`201808_data`$Page_Name))])
w9<-as.numeric(`201809_data`$WOW_COUNT[which(grepl("^陳其邁 Chen Chi-Mai$",`201809_data`$Page_Name))])
w9<-sum(w9)
w10<-sum(`201810_data`$WOW_COUNT[which(grepl("^陳其邁 Chen Chi-Mai$",`201810_data`$Page_Name))])
w11<-sum(`201811_data`$WOW_COUNT[which(grepl("^陳其邁 Chen Chi-Mai$",`201811_data`$Page_Name))])
w12<-as.numeric(`201812_data`$WOW_COUNT[which(grepl("^陳其邁 Chen Chi-Mai$",`201812_data`$Page_Name))])
w12<-sum(w12)
w13<-0

l1<-sum(`201801_data`$LOVE_COUNT[which(grepl("^陳其邁 Chen Chi-Mai$",`201801_data`$Page_Name))])
l2<-sum(`201802_data`$LOVE_COUNT[which(grepl("^陳其邁 Chen Chi-Mai$",`201802_data`$Page_Name))])
l3<-as.numeric(`201803_data`$LOVE_COUNT[which(grepl("^陳其邁 Chen Chi-Mai$",`201803_data`$Page_Name))])
l3<-sum(w3)
l4<-sum(`201804_data`$LOVE_COUNT[which(grepl("^陳其邁 Chen Chi-Mai$",`201804_data`$Page_Name))])
l5<-as.numeric(`201805_data`$LOVE_COUNT[which(grepl("^陳其邁 Chen Chi-Mai$",`201805_data`$Page_Name))])
l5<-sum(l5)
l6<-sum(`201806_data`$LOVE_COUNT[which(grepl("^陳其邁 Chen Chi-Mai$",`201806_data`$Page_Name))])
l7<-sum(`201807_data`$LOVE_COUNT[which(grepl("^陳其邁 Chen Chi-Mai$",`201807_data`$Page_Name))])
l8<-sum(`201808_data`$LOVE_COUNT[which(grepl("^陳其邁 Chen Chi-Mai$",`201808_data`$Page_Name))])
l9<-as.numeric(`201809_data`$WOW_COUNT[which(grepl("^陳其邁 Chen Chi-Mai$",`201809_data`$Page_Name))])
l9<-sum(l9)
l10<-sum(`201810_data`$LOVE_COUNT[which(grepl("^陳其邁 Chen Chi-Mai$",`201810_data`$Page_Name))])
l11<-sum(`201811_data`$LOVE_COUNT[which(grepl("^陳其邁 Chen Chi-Mai$",`201811_data`$Page_Name))])
l12<-as.numeric(`201812_data`$LOVE_COUNT[which(grepl("^陳其邁 Chen Chi-Mai$",`201812_data`$Page_Name))])
l12<-sum(l12)
l13<-0

like_han<-data.frame(month=c(1:12,13),count=c(s1,s2,s3,s4,s5,s6,s7,s8,s9,s10,s11,s12,s13,w1,w2,w3,w4,w5,w6,w7,w8,w9,w10,w11,w12,w13,l1,l2,l3,l4,l5,l6,l7,l8,l9,l10,l11,l12,l13),
                     types=c('like','like','like','like','like','like','like','like','like','like','like','like','like','wow','wow','wow','wow','wow','wow','wow','wow','wow','wow','wow','wow','wow','love','love','love','love','love','love','love','love','love','love','love','love','love'))

p1 <- ggplot(like_han, aes(x =month, y =count,colour=types))+ geom_line()+ scale_colour_brewer(palette = "Set1")
p1


library(readr)
tt<-levels(`201811_data`$Type)
data11<-subset(`201811_data`,grepl("柯文哲", `201811_data`$Page_Name) == TRUE)
ab1<-filter(`data11`,`data11`$Type==tt[1])
ab2<-filter(`data11`,`data11`$Type==tt[2])
ab3<-filter(`data11`,`data11`$Type==tt[3])
ab4<-filter(`data11`,`data11`$Type==tt[4])
ab5<-filter(`data11`,`data11`$Type==tt[5])
ab<-data.frame(x=c(nrow(ab1),nrow(ab2),nrow(ab3),nrow(ab4),nrow(ab5)))
pie(ab$x, labels = c(tt))

library(tidyverse)
VideoMatrix <- subset(`201811_data`,`201811_data`$Type == "video")
kvideo = subset(VideoMatrix,grepl("柯文哲", VideoMatrix$Page_Name) == TRUE)
tvideo = subset(VideoMatrix,grepl("丁守中", VideoMatrix$Page_Name) == TRUE)

kcomment = kvideo[,c(2,13,15)]
tcomment = tvideo[,c(2,13,15)]
ktComment = rbind(kcomment, tcomment)

library(kableExtra)
kable(head(ktComment))

library(ggplot2)


ktmessage = ktComment %>% group_by(Page_Name) %>% 
  mutate(messageByName = paste0(Message, collapse = ""))

id = which(duplicated(ktmessage$Page_Name) == FALSE)

ktmessageAll = ktmessage[id,c(1,4)]
kable(head(ktmessageAll))


library(jiebaRD)
library(jiebaR)

cutter <- worker("tag")

# 自建字典
dic = c("柯文哲", "柯p", "台北人")
new_user_word(cutter, dic)#將韓國瑜、國瑜、高雄人、作為分詞依據

myFUN<- function(str) {
  str = gsub("[A-Za-z0-9]", "", str)
  seg = cutter[str]
  id = which(nchar(seg) > 1)
  result = seg[id]
}

segment = apply(matrix(ktmessageAll$messageByName), 1, myFUN)

R = table(segment[[1]])
L = table(segment[[2]])
M_R = merge(x = R, y = L, by = "Var1", all = TRUE)
DTM_H = merge(x = M_R, y = table(segment[[3]]), by = "Var1", all = TRUE)
DTM_H[is.na(DTM_H)] <- 0
rownames(DTM_H) = DTM_H$Var1
DTM_H = DTM_H[,-1]
library(topicmodels)
dtm_lda <- LDA(t(DTM_H), k = 8, control = list(seed = 1234))
library(tidytext)
dtm_topics <- tidy(dtm_lda, matrix = "beta")
library(magrittr)
library(dplyr)


top_terms <- dtm_topics %>%
  group_by(topic) %>%
  top_n(10, beta) %>%
  ungroup() %>%
  arrange(topic, -beta)

top_terms %>%
  mutate(term = reorder(term, beta)) %>%
  ggplot(aes(term, beta, fill = factor(topic))) +
  geom_col(show.legend = FALSE) +
  facet_wrap(~ topic, scales = "free") +
  coord_flip() +
  theme(axis.text.y=element_text(colour="black", family="Heiti TC Light"))