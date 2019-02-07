dist = []
dist.append(0)
dist.extend(list(map(int, input().split())))

sumList = []

for j in range(1, 6):
    for i in range(0, 5):
        if(i >= j):
            sumList.append(sum(dist[j:i + 1]))
        else:
            sumList.append(sum(dist[i+1:j]))
    print(' '.join(list(map(str, sumList))))
    sumList = []
