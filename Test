# 1.請設計一個程式由鍵盤讀入:10組數字
# a) 依照輸入次序依序印出
# b) 排序依照由大到小依序印出
# c)將每個數字轉成2 or 8 or 16進制印出
print("第一題解答")
Math = []
i = 0
while i < 10:
  Math1 = int(input("請輸入數字=%d" % i))
  Math.append(Math1)
  i += 1
print("依照輸入次序依序印出 =",Math)
Math.sort(reverse=True)
print("排序依照由大到小依序印出 =",Math)
for j in range(len(Math)):
  print("轉為二進制 {:<10} 轉為八進制 {:^10} 轉為十六進制 {:>5}".format(bin(Math[j]),oct(Math[j]),hex(Math[j])))

# 2.設計一個程式由鍵盤讀入: 長/寬 以及圓半徑 
# a) 計算四邊形/圓面積及體積(格式化輸出小數點取3位)
print("第二題解答")
l = int(input("請輸入長:"))
w = int(input("請輸入寬:"))
r = int(input("請輸入圓半徑:"))
pi = 3.14159265359
print("四邊形面積=%.3f" % (w*l))
print("圓面積=%3f" % (pi * r ** 2))
print("體積=%.3f" % ((4/3) * pi * r ** 3))

# 3.建立5筆字典資料: 資料包含:學號/姓名/性別/生日/電話/地址/email 
# 格式化輸出(每一資料靠左對齊)印出
print("第三題解答")
Data = {"1號同學":{
    "學號":"1001",
    "姓名":"張小明",
    "性別":"女性",
    "生日":"81年08年11日",
    "電話":"0978-121-331",
    "地址":"厚德國小",
    "Email":"qwer0@gmail.com"},
    "2號同學":{
    "學號":"1002",
    "姓名":"張小風",
    "性別":"女性",
    "生日":"82年11年02日",
    "電話":"0912-452-584",
    "地址":"二重國中",
    "Email":"qwer123@gmail.com"},
    "3號同學":{
    "學號":"1003",
    "姓名":"王小明",
    "性別":"男性",
    "生日":"80年07年12日",
    "電話":"0946-511-659",
    "地址":"開南商工",
    "Email":"sdfg1235@gmail.com"},
    "4號同學":{
    "學號":"1004",
    "姓名":"林筱芯",
    "性別":"女性",
    "生日":"85年12年01日",
    "電話":"0941-421-054",
    "地址":"莊敬高職",
    "Email":"vbnm548@gmail.com"},
    "5號同學":{
    "學號":"1005",
    "姓名":"劉評委",
    "性別":"男性",
    "生日":"75年04年04日",
    "電話":"0956-159-151",
    "地址":"育達高職",
    "Email":"abcd1234@gmail.com"}
}
for name, name_data in Data.items():
  for n1, n2 in name_data.items():
    print(n1,end=" ")
    print(n2)

# 4.將1~1500 :偶數以 tuple存入:
# a)計算長度 b)取出最大值 c)最小值 d)將tuple資料轉成串列
print("第四題解答")
double = []
for l in range(2 ,1500 ,2):
  double.append(l)
print("長度=",len(double))
print("最大值=",max(double))
print("最小值=",min(double))
double1 = tuple(double)
print("將tuple資料轉成串列=",double1)

# 5.寫出 9*9*9 乘法表
print("第五題解答")
for q in range(1,10):
    print(" ")
    for w in range(1,10):
        for r in range(1,10):
          print("{:^1d}*{:^1d}*{:^1d}={:^4d}".format(q ,w ,r ,q*w*r),end=" ")
        print(" ")

# 6.輸入5筆資料(5組欄位: name, age, address, sex, score): 
# a)將資料 壓縮成一個list, 印出
# b)再將資料解壓縮成5筆資料
print("第六題解答")
Data1 = ["王昱翔",22,"中和公寓","男性",60]
Data2 = ["楊承恩",15,"桃園公寓","男性",87]
Data3 = ["蔡白樺",27,"南投大飯店","男性",84]
Data4 = ["洪哲林",45,"美國紐約","男性",99]
Data5 = ["林姥獅",23,"金門監獄","女性",45]
Data_all = zip(Data1,Data2,Data3,Data4,Data5)
print("將資料壓縮成一個list印出 =",list(Data_all))
q1,q2,q3,q4,q5 = zip(*zip(Data1,Data2,Data3,Data4,Data5))
print("再將資料解壓縮成5筆資料 =",q1,q2,q3,q4,q5)

# 7.請寫程式計算一篇文章中單字出現次數
print("第七題解答")
song = '''Are you sleeping, are you sleeping, Brother John, Brother John?
Morning bells are ringing, morning bells are ringing.
Ding ding dong, Ding ding dong.'''


songlow = song.lower()
for h in songlow:
  if h in '.,?，':
    songlow = songlow.replace(h,"")
songlist = songlow.split()
mydict = {wd:songlist.count(wd) for wd in songlist}
print(mydict)

# 8.有三個課程:
print("第八題解答")
國文 = {"Peter", "Norton", "Kevin", "Mary", "John", "Nelson", "Damon", "Tom", "James", "Alson", "Michell", "Micro", "Bidy", "Paul"}
英文 = {"Peter", "Mary", "John", "Nelson", "Christina", "Simon", "Bidy", "Tom", "James", "Alson", "Wen"}
物理 = {"Eric", "Norton", "Mary", "Paul", "Simon", "Jelson", "Tom", "James", "Alson", "Kazxil", "Linda", "Christ"}
# a)同時參加三個課程名單
# b)同時參加國文/物理但沒參加 英文 名單
# c)至少選2個課程名單並依照字母做排序輸出

class0 = 國文 & 英文 & 物理
class1 = 國文 & 物理 | 英文
class2 = (國文 & 英文) | (英文 & 物理) | (國文 & 物理)
x = [class0 ,class1 ,class2]
z = ["同時參加三個課程名單 =","同時參加國文&物理但沒參加英文名單 =","至少選2個課程名單並依照字母做排序輸出 ="]
for y in range(len(x)):
  print("",z[y]," ".join(sorted(x[y])))
  
# 2.	設計一個程式由鍵盤讀入: 長L/寬W 以及圓半徑R  
# a) 計算柱狀面積及體積(格式化輸出小數點取3位) (測試取L=W=10, R=5)
l = int(input("請輸入L的數字 ="))
w = int(input("請輸入W的數字 ="))
r = int(input("請輸入R的數字 ="))
pi = 3.14159265359
print("圓面積=%.3f" % (pi * r ** 2))
print("體積=%.3f" % ((pi * r ** 3)*l))

# 4. 將1~1500 :偶數以 tuple存入:
# a)計算長度 b)取出最大值  c)最小值 d)將tuple資料轉成串列

math = []
for i in range(0,1501,2):
  math.append(i)
ta = tuple(list(math))
print("a)計算長度:",len(ta))
print("b)取出最大值:",max(ta))
print("c)取出最小值:",min(ta))
print("d)將tuple資料轉成串列:",(list(tuple(ta))))

# 6. 輸入5筆資料(5組欄位: name, age, address, sex, score): 
# a)將資料 壓縮成一個list, 印出
# b)再將資料解壓縮成5筆資料
Data1 = ["王昱翔",22,"中和公寓","男性",60]
Data2 = ["楊承恩",15,"桃園公寓","男性",87]
Data3 = ["蔡白樺",27,"南投大飯店","男性",84]
Data4 = ["洪哲林",45,"美國紐約","男性",99]
Data5 = ["林姥獅",23,"金門監獄","女性",45]
Data_all = zip(Data1,Data2,Data3,Data4,Data5)
print("將資料壓縮成一個list印出 =",list(Data_all))
q1,q2,q3,q4,q5 = zip(*zip(Data1,Data2,Data3,Data4,Data5))
print("再將資料解壓縮成5筆資料 =",q1,q2,q3,q4,q5)

# 7. 請寫程式計算下篇文章中每個單字出現次數
text = """A poet is a person who creates poetry. Poets may describe themselves as such or be described as such by others. A poet may simply be a writer of poetry, or may perform their art to an audience.

Postmortal fictional portrait of Slovak poet Janko Kráľ (1822–1876) – an idealized romanticized picture of "how a real poet should look" in Western culture.
The work of a poet is essentially one of communication, either expressing ideas in a literal sense, such as writing about a specific event or place, or metaphorically. Poets have existed since antiquity, in nearly all languages, and have produced works that vary greatly in different cultures and periods.[1] Throughout each civilization and language, poets have used various styles that have changed through the course of literary history, resulting in a history of poets as diverse as the literature they have produced."""
songlow = text.lower()
for h in songlow:
  if h in '.,?，':
    songlow = songlow.replace(h,"")
songlist = songlow.split()
mydict = {wd:songlist.count(wd) for wd in songlist}
print(mydict)

# 8. 有三個課程:
國文 = {"Peter", "Norton", "Kevin", "Mary", "John", "Nelson", "Damon", "Tom", "James", "Alson", "Michell", "Micro", "Bidy", "Paul"}
英文 = {"Peter", "Mary", "John", "Nelson", "Christina", "Simon", "Bidy", "Tom", "James", "Alson", "Wen"}
物理 = {"Eric", "Norton", "Mary", "Paul", "Simon", "Jelson", "Tom", "James", "Alson", "Kazxil", "Linda", "Christ"}
# a) 同時參加三個課程名單
# b) 同時參加國文/物理但沒參加 英文 名單
# c) 至少選2個課程名單並依照字母做排序輸出
class0 = 國文 & 英文 & 物理
class1 = 國文 & 物理 | 英文
class2 = (國文 & 英文) | (英文 & 物理) | (國文 & 物理)
x = [class0 ,class1 ,class2]
z = ["同時參加三個課程名單 =","同時參加國文&物理但沒參加英文名單 =","至少選2個課程名單並依照字母做排序輸出 ="]
for y in range(len(x)):
  print("",z[y]," ".join(sorted(x[y])))
