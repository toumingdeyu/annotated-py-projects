# flask-annotated
flask 源码注释版本. flask 是一个非常赞的Python web framework.


## 源码注解说明:

### 版本挑选:

- `0.1`: 任何项目,第一个版本提交,都值得深入学习.
- `0.4`: 单文件的最后一个版本.代码1k+行.值得和 0.5 版本作对比.
- `0.5`: 第一次模块化重构,单文件拆分成多模块.学习项目模块组织架构.
- `0.10.1`: 最新版本,对比学习经过多次重构后,最终成型的项目代码.
- 其他版本,可能会作为对比用,不会去详细注解



## flask 官方资源

- [官方文档](http://flask.pocoo.org/)
- [flask - github](https://github.com/mitsuhiko/flask)
- [flask - releases](https://github.com/mitsuhiko/flask/releases)



## flask 版本说明:

- flask 0.1 ~ 0.4 版本, 整个框架代码,只有一个单文件.
- flask 0.5 版本, 开始拆分成多文件结构.

### [flask 0.1](./flask-0.1,0.4/flask-0.1.py)

- 发布时间: 16 Apr 2010
- 代码行数: 539 (含注释,不含空行)
- 点评:
    - 代码非常精简.
    - 一个mini的web 框架模型.

### flask 0.2, 0.3 不再注解.

- 点评:
    - 比0.1版本新增了几个模块,优化了部分代码.
    - 代码少量更新.用IDE 作文件对比后, 可知代码更新很少,只是在重构代码.
    - 故 0.2, 0.3 版本的代码,不再注解,跳过.直接注解 0.4版本.


### [flask 0.4](./flask-0.1,0.4/flask-0.4.py)

- 发布时间: 18 Jun 2010
- 代码行数: 1238 (含注释,不含空行)
- 点评:


### [flask 0.5](./flask-0.5)

- 发布时间: 6 Jul 2010
- 代码行数: 1594 (含注释,不含空行)
- 点评:
    - 第一次对代码结构作了模块化拆分.(之前的版本,都是单文件)
    - 对比 0.4 版本, 没多几行代码.(注意学习模块化拆分思想)


### [flask 0.7]()

- 发布时间: 28 Jun 2011
- 代码行数: 2613
- 点评:
    - 此版本功能模块已经非常丰富:
        - blueprint
        - logging
        - session
        - template
        - view
        - test
        - wrapper
    - 与其他框架比较:
        - django: 显然不用比,这无比臃肿的货
        - tornado: 比之,较少
        - bottle.py: 并不多(bottle也有3k~1w行)
        

### [flask 0.10.1]()

- 发布时间: 14 Jun 2013
- 代码行数: 8484-4043(测试) = 4441
- 点评:
    - 截至当前: 2016-01-27, 这依然是当前发布最新版本代码.(此版本2013年就发布了)
    - 可以看到,代码并没有想象中的多.flask官方是属于比较保守的发版本策略.
    - 对比 0.7 版本:
        - 模块结构并无重大调整
        - 基本上没有添加太多内容.(可能是模块重构,优化居多)
        

