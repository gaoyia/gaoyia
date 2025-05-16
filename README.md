<p align="center">
  <img src="https://komarev.com/ghpvc/?username=gaoyia&color=brightgreen">
</p>
<h3 align="center">👋 Hello! I'm gaoyi.</h3>
<p align="center">
  <a href="https://github.com/gaoyia">GitHub</a>
</p>

<h3 align="center">:chart_with_upwards_trend:Github Stats:chart_with_upwards_trend:</h3>

<p align="center">
  <a href="https://github.com/gaoyia" title="gaoyia's GitHub Stats">
    <img src="https://github-readme-stats.vercel.app/api?username=gaoyia&show_icons=true&count_private=true&layout=compact&theme=default">
  </a>
  <br/>
  <a href="https://github.com/gaoyia" title="Most Used Languages">
    <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=gaoyia&layout=compact&count_private=true&theme=default">
  </a>
</p>

# 编程哲学与管理思想

## 1. 没有消息就是好消息（No news is good news）
  来自Linux/Unix系统的设计思想，在系统正常运行时不需要对外输出消息，输出消息同样会有一定的性能开销且影响程序运行。<br>
  类比为员工在执行任务时需要做出额外的工作汇报，降低程序运行效率。<br>
  额外的输出会为用户或主进程带来干扰，需要对其输出内容分配内存空间。分配额外的注意力关注输出内容。<br>
  同样主线程在频繁的线程切换（工作内容切换）时会严重降低运行效率。<br>
  当输出内容过于繁杂时，容易忽略掉重要信息。<br>
  
## 2. 复杂度只会转移，不会凭空消失——复杂度守恒定律
  每个应用程序都具有其内在的、无法简化的复杂度。 无论在产品开发环节还是在用户与产品的交互环节，这一固有的复杂度都无法依照我们的意愿去除，只能设法调整、平衡。<br>
  例如以前的电视遥控器，有很多按钮。但电视功能比较简单，现在的智能电视，遥控器比较简单，但功能更复杂。<br>
  因此，本人比较排斥类似低代码平台的概念，本质是增加了系统复杂度，降低了业务变更的复杂度，同时并未减小业务本身的复杂度。<br>
  复杂度增加意味着系统可维护性降低，极大的增加开发成本。<br>
  如果有明确的复杂度边界也是可以做的，但要明确指出低代码绝不是解决问题的银弹<br>

## 3. 约定大于配置

> 总结：文档很重要!.

  该原则来自Spring Boot, 它强调使用默认约定和规则，减少开发者需要做的显式配置。根据这一原则，大部分情况下，开发者只需关注那些不符合默认约定的配置，而不需要为每个细节都进行显式配置。
  ### "约定大于配置"的优势：
  1. 提高开发效率： 通过遵循默认约定，开发者可以快速启动项目并进行开发，无需花费大量时间在繁琐的配置上。
  2. 减少决策负担： "约定大于配置"减少了开发者需要做出的决策，使开发过程更加流畅，不需要在每个细节上做出选择。
  3. 减少错误： 默认约定可以减少配置错误的机会，因为开发者只需要在特定情况下进行配置，从而降低了出错的可能性。

  日常开发中约定也是一项很重要的内容。我们需要显示的把约定记录下来形成文档，特别是在早期构建项目的时候。这些约定都需要同步给所有开发人员使其遵守约定。不符合约定的我们需要及时改正避免产生的问题加重。<br>
  如果这些约定没有形成文档，这些代码就像「魔法数字-魔数」（magic number）一样让人难以捉摸其原理。我将其称之为「魔法代码-魔码」（magic code）。<br>


