---
title: 'Insert title here'
key: d8fcd4c930027fa4e1c3870c7e7e0ff1
video_link:
    mp4: 'https://s3.amazonaws.com/videos.datacamp.com/raw/735_intro_to_python/v6/735_ch1_1.mp4'
    hls: 'https://s3.amazonaws.com/videos.datacamp.com/transcoded/735_intro_to_python/v6/hls-735_ch1_1.master.m3u8'
---

## Hello Python!

```yaml
type: TitleSlide
key: f743ca8c41
```

`@lower_third`
name: Hugo Bowne-Anderson
title: Data Scientist at DataCamp

`@script`
Hi, my name is Hugo and I'll be your host for Introduction to Python for Data Science.

I'm a data scientist and educator at DataCamp and host of the DataFramed podcast, which you must check out.

---

## How you will learn

```yaml
type: FullSlide
key: 30ee08a725
disable_transition: true
```

`@part1`
![im1.png](https://assets.datacamp.com/production/repositories/288/datasets/da7bde68581f6ad120f09b5007fac89d09c1b3cf/mobile_1_1.PNG)

`@script`
In this course,

---

## How you will learn

```yaml
type: FullSlide
key: a093f0b659
disable_transition: true
```

`@part1`
![im2.png](https://assets.datacamp.com/production/repositories/288/datasets/b0b5c9845caa047f0843510d6f3927f5fe5639c3/mobile_1_2.PNG)

`@script`
you will learn Python for Data Science through video lessons,

---

## How you will learn

```yaml
type: FullSlide
key: cff110c262
disable_transition: true
```

`@part1`
![im3.png](https://assets.datacamp.com/production/repositories/288/datasets/05247ce1f8871bcc07e05f179395a4b457b017ab/mobile_1_5.PNG)

`@script`
like this one, and interactive exercises.

---

## How you will learn

```yaml
type: FullSlide
key: 42962f0d17
disable_transition: true
```

`@part1`
![im4.png](https://assets.datacamp.com/production/repositories/288/datasets/323313be6729ec216e4a6c77fdcc9641dbbffd61/mobile_1_6.PNG)

`@script`
You get your own Python session where you can experiment and

---

## How you will learn

```yaml
type: FullSlide
key: 3262829f32
disable_transition: true
```

`@part1`
![im5.png](https://assets.datacamp.com/production/repositories/288/datasets/73ea66f968e43361433e54d8f2c4ec3bd8a7b85c/mobile_1_9.PNG = 35)

`@script`
try to come up with the correct code to solve the instructions.

---

## How you will learn

```yaml
type: FullSlide
key: fde7ff1ea9
disable_transition: true
```

`@part1`
![im6.png](https://assets.datacamp.com/production/repositories/288/datasets/7da20776376e265adb1e20f803882b66a4c7edf3/mobile_1_10.PNG = 35)

`@script`
You're learning by doing,

---

## How you will learn

```yaml
type: FullSlide
key: c9dd1edd75
disable_transition: true
```

`@part1`
![im7.png](https://assets.datacamp.com/production/repositories/288/datasets/7da20776376e265adb1e20f803882b66a4c7edf3/mobile_1_10.PNG = 35)

`@script`
while receiving customized

---

## How you will learn

```yaml
type: FullSlide
key: b6b5c151b9
disable_transition: true
```

`@part1`
![im8.png](https://assets.datacamp.com/production/repositories/288/datasets/f8557f66113706f8808ddb9b793a01643310bcd6/mobile_1_11.PNG = 35)

`@script`
and instant feedback on your work.

---

## Python

```yaml
type: TwoColumns
key: 3f23b93572
```

`@part1`
- Guido Van Rossum{{1}}

- General Purpose: build anything{{3}}

- Open Source! Free!{{4}}

- Python Packages, also for Data Science{{5}}

	- Many applications and fields{{6}}

- Version 3.x - https://www.python.org/downloads/{{7}}

`@part2`
![guido-hba.png](https://assets.datacamp.com/production/repositories/288/datasets/fb3e4b8dc114529dafffb37d33f2b2244210d40f/guido-hba.png){{2}}

`@script`
Python was conceived by Guido Van Rossum. Here, you can see a photo of me with Guido. What started as a hobby project, soon became a general purpose programming language: nowadays, you can use Python to build practically any piece of software. But how did this happen? Well, first of all, Python is open source. It's free to use. Second, it's very easy to build packages in Python, which is code that you can share with other people to solve specific problems. Throughout time, more and more of these packages specifically built for data science have been developed. Suppose you want to make some fancy visualizations of your company's sales. There's a package for that. Or what about connecting to a database to analyze sensor measurements? There's also a package for that.
People often refer to python as the swiss army knife of programming languages as you can do almost anything with it.
In this course, we'll start to build up your data science coding skills bit by bit, so make sure to stick around to see how powerful the language can be.

Currently, there are two common versions of Python, version 2-point-7 and 3-point-5 and later. Apart from some syntactical differences, they are pretty similar, but as support for version 2 will fade over time, our courses focus on Python 3. To install Python 3 on your own system, follow the steps at this URL.

---

## IPython Shell

```yaml
type: FullSlide
key: 43a91a7217
```

`@part1`
Execute Python commands

![ch_1_1_slides.002.png](https://assets.datacamp.com/production/repositories/288/datasets/4acc9ee51c7a66a777781c638b745db375f221a8/mobile_2_1.PNG)

`@script`
Now that you're all eyes and ears for Python, let's start experimenting. I'll start with the Python shell, a place where you can type Python code and immediately see the results. In DataCamp's exercise interface, this shell is embedded here.

---

## IPython Shell

```yaml
type: FullSlide
key: 524e4c20a7
disable_transition: true
```

`@part1`
![im_1.png](https://assets.datacamp.com/production/repositories/288/datasets/7708afd8600d20e50f6bc2056c1d1bc48c8d9315/mobile_2_2_2.PNG = 35)

`@script`
Let's start off simple and use Python as a calculator. Let me type 4 + 5

---

## IPython Shell

```yaml
type: FullSlide
key: a4f0f4cf69
disable_transition: true
```

`@part1`
![im_2.png](https://assets.datacamp.com/production/repositories/288/datasets/bcd9ce205651795b8269aed4f3781429179436f7/mobile_2_2.PNG = 35)

`@script`
and hit Enter.

---

## IPython Shell

```yaml
type: FullSlide
key: b1718925d8
disable_transition: true
```

`@part1`
![im_3.png](https://assets.datacamp.com/production/repositories/288/datasets/ac8add53c6b7f9414a39bc746fd2ed02676c6d4b/mobile_2_3.PNG = 35)

`@script`
Python interprets what you typed and prints the result of your calculation, 9. The Python shell that's used here is actually not the original one; we're using IPython, short for Interactive Python, which is some kind of juiced up version of regular Python that'll be useful later on.

IPython was created by Fernando Pérez and is part of the broader Jupyter ecosystem. Apart from interactively working with Python, you can also have Python run so called

---

## Python Script

```yaml
type: FullSlide
key: 78ef256bc0
```

`@part1`
- Text Files - .py{{1}}

- List of Python Commands{{2}}

- Similar to typing in IPython Shell{{3}}

`@script`
python scripts. These python scripts are simply text files with the extension (dot) py. It's basically a list of Python commands that are executed, almost as if you where typing the commands in the shell yourself, line by line. Let's put the command from before in a script now,

---

## Python Script

```yaml
type: FullSlide
key: 719d500511
```

`@part1`
![im_2.png](https://assets.datacamp.com/production/repositories/288/datasets/1b44ea76910eb712757d38d2f3d554511b533ef6/mobile_2_4.PNG)

`@script`
that can be found here in DataCamp's interface.

---

## Python Script

```yaml
type: FullSlide
key: 717d124175
disable_transition: true
```

`@part1`
![im_4.png](https://assets.datacamp.com/production/repositories/288/datasets/bddf32c89d2ca90e9cf7d3bebb210c9980f8f285/mobile_2_5.PNG = 35)

`@script`
The next step is executing the script, by clicking 'Submit Answer'.

---

## Python Script

```yaml
type: FullSlide
key: 373fd0a03d
disable_transition: true
```

`@part1`
![im_5.png](https://assets.datacamp.com/production/repositories/288/datasets/e830cd989e9b4e032e7c6d91215c91290453ad4e/mobile_2_6.PNG = 35)

`@script`
If you execute this script in the DataCamp interface, there's nothing in the output pane. That's because you have to explicitly use print inside scripts if you want to generate output during execution. Let's wrap our previous calculation in a print call,

---

## Python Script

```yaml
type: FullSlide
key: c7a9d02fb6
disable_transition: true
```

`@part1`
![im_6.png](https://assets.datacamp.com/production/repositories/288/datasets/cacf5f3a4407778e66d76faab01869be914346c4/mobile_2_7_2.PNG = 35)

`@script`
and rerun the script.

---

## Python Script

```yaml
type: FullSlide
key: 65dc2d6b9c
disable_transition: true
```

`@part1`
![im_7.png](https://assets.datacamp.com/production/repositories/288/datasets/4b38b8f84d7eb7a4fc8956bb3a6af4033a95b658/mobile_2_7.PNG = 35)

`@script`
This time, the same output as before is generated, great! Putting your code in Python scripts instead of manually retyping every step interactively will help you to keep structure and avoid retyping everything over and over again if you want to make a change; you simply make the change in the script, and rerun the entire thing.

---

## DataCamp Interface

```yaml
type: FullSlide
key: 693ba1cd14
```

`@part1`
![ch_1_1_slides.001.png](https://assets.datacamp.com/production/repositories/288/datasets/b27d720dd9d1113e12950134eab071cc2e60cb0c/IMG_1786.PNG)

`@script`
Now that you've got an idea about different ways of working with Python, I suggest you head over to the exercises.

---

## DataCamp Interface

```yaml
type: FullSlide
key: 0ee37fba22
disable_transition: true
```

`@part1`
![ch_1_1_slides.002.png](https://assets.datacamp.com/production/repositories/288/datasets/4acc9ee51c7a66a777781c638b745db375f221a8/mobile_2_1.PNG)

`@script`
Use the IPython Shell for experimentation,

---

## DataCamp Interface

```yaml
type: FullSlide
key: a88cc5ac35
disable_transition: true
```

`@part1`
![ch_1_1_slides.003.png](https://assets.datacamp.com/production/repositories/288/datasets/1b44ea76910eb712757d38d2f3d554511b533ef6/mobile_2_4.PNG)

`@script`
and use the Python script editor to code the actual answer. If you click Submit Answer, your script will be executed and checked for correctness.

---

## Let's practice!

```yaml
type: FinalSlide
key: 7445cd202e
```

`@script`
Get coding and don't forget to have fun!
