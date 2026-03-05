# AI Engineer Portfolio

## Goal
- Become internship-ready AI Engineer

## Weekly log
- Day 1: Create Repo, write README.md and complete Kaggle Python lessons.
- Day 2: Completed the Kaggle Python and Pandas lessons.

## Review
- Day 1: we have to git pull before git push anything to github. We have a procesion:
    + git pull 
    + git add <anything we want to up>
    + git commit -m "..."
    + git push 

### Day 1 — Git workflow (before pushing to GitHub)

Before pushing, we should pull the latest changes from the remote repository to avoid conflicts.

**Process:**
1. `git pull`
2. `git add <files_you_want_to_upload>`
3. `git commit -m "..."`  
4. `git push`

### Day 2 — Pandas basics (create, read, write)

We learned how to create, read, and write data using **pandas**.

#### Reading data
To read a CSV file, use:

```python
df = pd.read_csv("file.csv")
```

#### Selecting data with **iloc** and **loc**
**iloc (index-based selection)**

- **iloc** uses integer positions to select data. 

**Example**

```python
dataframe.iloc[x, y] 
```

- **x**: row we want to get, x can list, number and slicing
- **y: column we want to get

**loc (label-based selection)**

- **loc** uses labels to get data, it's also commonly used for boolean filtering, we use **&** with **and** and **|** with **or**

**Example**
```python
dataframe.loc[x, label]
dataframe.loc[dataframe.country == "Viet Nam"]
```
- **x**: row we want to get, x can list, number and slicing
- **label**: name of column we want to get, it can string, list

