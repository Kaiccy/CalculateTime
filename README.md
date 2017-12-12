# CalculateTime
计算某个时间到现在的时间差

此方法实现的是摸个时间距离现在的时间差，返回字符串分别为：相比今天为，昨天，前天，前天之前就返回日期，如果是今天那就返回，几小时前，几分钟前

使用方法（举栗）：
  CaculateTime *tool = [[CaculateTime alloc] init];
    label.text = [tool timeString:@"2012-06-12 12:23:34"];
    
注意：使用此方法时，传入的字符串参数格式必须为 yyyy-MM-dd HH:mm:ss
  
