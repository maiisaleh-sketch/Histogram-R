# Histogram-R

ggplot(diamonds,  aes(x= price)) + geom_histogram(bins = 30, file = "red" , colour = "black")+
  theme_light() +
  xlab("Price") +
  ylab("count") +
  ggtitle("The title")
