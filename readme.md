![](https://www.xudongz.com/static/840d53a20dfaa623679fbe6497731fec5a93f3f08de11ad25ff703be8c1867cf.png)

## Installation

```
go install xudongz.com/code/gitstreak@latest
```

## Usage

You can use gitsteak to display the graph for any number of repositories.

```
gitstreak path/to/repo1 path/to/repo2
```

You can limit it to a specific user by specifying their email address.

```
gitstreak -author user@example.org path/to/repo
```

If you have a single directory with all your repositories, you can easily
include each repository.

```
gitstreak -author user@example.org path/to/parent/*
```

You can define an alias within your `.bashrc` file if you do not want to specify
a list of repository every time.

## Example Graphs

```
gitstreak go
```

![](https://www.xudongz.com/static/fcf9ccd995a3058d29f6f7a11767db09cbb6856e6c19879d29d25acd8fc40531.png)

```
gitstreak linux
```

![](https://www.xudongz.com/static/e0eb55d708799132ef54a3b5ef9afd4885209d045dd12417df1232837c79f95a.png)

```
gitstreak -author torvalds@linux-foundation.org linux
```

![](https://www.xudongz.com/static/87fa55217c286e89205b2d02b1e855f8a429d3ac98262336ae6ea50236bb0650.png)

```
gitstreak node
```

![](https://www.xudongz.com/static/f7fdf76e9cd981d32cccb091b1253e8b035459613b1b9d601882e073399c02aa.png)

## Author

[Xudong Zheng](https://www.xudongz.com/)
