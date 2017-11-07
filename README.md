7lab
Read test:
1. Read from: set=0,tag=0,0ffset=1 => hit = 0 Load row from ram and display result.
2. Read from: set=0,tag=1,offset=0 => hit = 0 Load row from ram and display(line not changed)
3. Write word 10 in: set=0,tag=0,0ffset=7 => Load row from ram(tag=1 not changed) and write word.
4. Read from: set=0,tag=1,offset=1 => hit = 0 Push row from cache in ram, then load row from ram and display result.
Write test:
1. Write 5 in: set=1,tag=0,offset=0 => hit = 0 Load row from cache, and then write word.
2. Write 10 in: set=1,tag=1,offset=0 => hit = 0 push row from cache in ram, then load row from ram and write word.
3. Write 15 in: set=1,tag=2,offset=0 => hit = 0 push row from cache in ram, then load row from ram and write word.
