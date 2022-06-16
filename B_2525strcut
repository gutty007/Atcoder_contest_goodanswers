#第4回 ドワンゴからの挑戦状 予選 問題B 2525文字列分解 300点
#問題文 https://atcoder.jp/contests/dwacon2018-prelims/tasks/dwacon2018_prelims_b

S=list(input())
count=0
S2=0
frag=0

for i in S:
  if i == "2":
    S2 += 1
    if count < S2:
      count=S2
  else:
    S2 += -1
    if S2 < 0:
      print(-1)
      S2=0
      frag=1
      break

if S2 !=0:
  frag=1
  print(-1)

if frag != 1:
  print(count)
