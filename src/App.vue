<script lang="ts" setup>
import { ChatBubbleLeftRightIcon } from "@heroicons/vue/24/solid";
</script>

<template>
  <section class="relative h-screen">
    <header
      class="fixed w-full px-6 h-6 border-b bg-[#fff9f1] border-[#f2ebe3]"
    ></header>
    <div class="fixed h-full w-6 border-r z-20 border-[#f2ebe3]"></div>
    <div class="fixed h-full w-6 border-l right-0 z-20 border-[#f2ebe3]"></div>
    <div
      class="h-[1px] w-full fixed lg:h-full lg:w-[1px] border-r border-dashed left-1/2 z-20 border-[#f2ebe3]"
    ></div>

    <!-- Content -->
    <div class="px-6 py-6 lg:px-8 grid grid-cols-1 lg:grid-cols-2 lg:gap-8 h-full">
      <!-- Introduction -->
      <div class="p-4 flex flex-col justify-between">
        <div>
          <img src="./images/red-logo.png" class="h-6 lg:h-8 mt-2 mb-4" />
          <div>
            <h1>
              真正的观点交锋——大师对谈之：《红猪》完成纪念，宫本茂VS宫崎骏
            </h1>
            <div class="flex italic my-6">
              <p class="text-3xl font-black text-black/10">”</p>
              <p class="py-4 content">
                本次采访刊载于1992年的《Fami-Maga》杂志（ Fami
                通之前日本最大的游戏杂志，已停刊）。在这次采访进行的时候，宫崎骏和吉卜力工作室刚刚完成了一部鸿篇巨制《红猪》。宫本茂和当时的
                Fami-Maga
                编辑一起看了这部电影，并于之后参观了吉卜力工作室与宫崎骏对谈。<br>这篇文章，就收录了两人对谈的部分内容。在《红猪》即将于国内上映之时，我特此翻译，廖表纪念。
              </p>
              <div class="flex items-end text-3xl font-black text-black/10">
                “
              </div>
            </div>
          </div>
        </div>
        <!-- Note -->
        <div class="hidden lg:flex flex-col gap-2 py-4">
          <p
            class="p-1 bg-black/70 flex justify-center text-white rounded-lg w-10 text-xs"
          >
            补充
          </p>
          <div class="flex note gap-2">
            <div>1.</div>
            <div>
              译者注：这篇文章没有标题党，真的是宫本茂VS宫崎骏，两人观点的激烈碰撞让场面一度失控。然后就是宫崎骏的单方面输出和宫本茂的答不上来。然而大师始终是大师，在这样的观点交锋中，宫本茂竟然学到了宫崎骏创作哲学的真谛，并且学以致用，创造了塞尔达开发者们奋斗一生的“空气感”。
            </div>
          </div>
          <div class="flex note gap-2">
            <div>2.</div>
            <div>
              原文地址：<a
                href="https://www.bilibili.com/read/cv24202714/?spm_id_from=333.1007.0.0"
                class="hover:bg-[#fa678e]/10"
                >https://www.bilibili.com/read/cv24202714/?spm_id_from=333.1007.0.0</a
              >
            </div>
          </div>
          <div class="flex note gap-2">
            <div>3.</div>
            <div>
              电影简介：<a
                href="https://movie.douban.com/subject/1291838/"
                class="hover:bg-[#00ac1b]/10"
                >https://movie.douban.com/subject/1291838/</a
              >
            </div>
          </div>
        </div>
      </div>

      <div class="px-4 w-full lg:hidden">
        <div
          class="h-[2px] w-full border-b border-[#f2ebe3] border-dashed"
        ></div>
      </div>

      <!-- Dialog -->
      <section class="p-4 flex flex-col gap-4 h-full lg:overflow-y-scroll">
        <div class="h-8 my-2 text-black/50 text-[15px] flex items-center gap-1">
          <ChatBubbleLeftRightIcon class="h-5 w-5 text-black/10" />左侧为<span
            class="max-w-[288px] lg:max-w-lg bg-red-500/5 px-1.5 py-0.5 rounded-lg border border-black/5 content shadow-sm"
            >宫本茂</span
          >，右侧为<span
            class="max-w-[288px] lg:max-w-lg bg-blue-500/5 px-1.5 py-0.5 rounded-lg border border-black/5 content shadow-sm"
            >宫崎骏</span
          >
        </div>
        <div class="flex gap-2">
          <div class="dialog-l">
            我太喜欢这部电影了。很难解释为何我会喜欢这部电影，也很难明确说出我到底喜欢它的哪个部分，然而这部电影对我来说毫无尿点。<br><br>
            从头到尾，我只需要去看而不用太多地去思考。我喜欢简单的镜头，比如一艘飞船停泊在水面上。
          </div>
        </div>

        <div class="flex gap-2 justify-end">
          <div class="dialog-r">是的，从某种程度上说，这是一部简单的电影。</div>
        </div>

        <div class="flex gap-2">
          <div class="dialog-l">
            我忍不住以游戏开发者的角度去看里面的狗斗场景。那种速度感是在游戏里很难去重现的。
          </div>
        </div>

        <div class="flex gap-2 justify-end">
          <div class="dialog-r">
            我没有为这部电影准备剧本。另外，在这部电影中，我没有什么想特别表达来强调的信息或者中心思想。<br><br>所以拍这部电影实际上是一个非常艰难且骇人的经历，因为我不确定我是否能给观众一个满意的交代。
          </div>
        </div>

        <div class="flex gap-2">
          <div class="dialog-l">
            在我们的领域，所有项目都是从侃大山开始的。我们也不会事先准备剧本。过去的时代，我们没有很多员工，劳动标准法也不那么严格。<br>
            <br>我们经常会在办公室待到差不多凌晨两点。我们也不干别的，只是互相随意交流着想法，然后说：“好吧，让我们明天来试试这个是不是可行。”然后我们就回家，总是这样。我们决定了明天要做什么并且这件事让我们很期待明天的上班。从某种程度上说，这是必要的准备阶段。<br>
            <br>但是现在，我们的员工人数增加了，我有点担心，毕竟不是每个人都像我们以前一样期待着来上班。
          </div>
        </div>

        <div class="flex gap-2 justify-end">
          <div class="dialog-r">
            可是，如果你需要团队作战，那里面就会有各种各样的人。有人可以成为团队的核心。也有人会成为团队核心的支持者。当然还有更多的人只会遵照命令行事。一部电影的质量取决于你能找到多少核心成员。<br><br>他们会说：“只有团队里的每一个人都付出所有，一个项目才会完成。”但事实并非如此。总有一些人不是真正喜欢这个项目。当我试图向他们交代新工作的时候，他们就会突然开始动手，假装正在工作。而当我不看着他们的时候，他们就会偷懒。我们把这样的员工称作“驴”（大笑）。但这很正常。<br><br>当人们在一起做某件事的时候你总会遇到各种各样的人。
          </div>
        </div>

        <div class="flex gap-2">
          <div class="dialog-l">
            在我们的行业里，有能力在适当的时候停止开发的人非常稀少。所以我经常会担心正在进行的项目因为我不确定他们是否能以正确的方式完成开发。
          </div>
        </div>

        <div class="flex gap-2 justify-end">
          <div class="dialog-r">
            我理解这种感受。当我们做《红猪》的时候，我也特别地担心。在制作早期阶段的某一天，我看着还没加入任何声效的电影，我不确定这个结局能不能令人满意。我开始想……“不！这个故事根本就没有结局！”我的脸变得苍白。我马上回家并且悲叹道：“我拍了一部令人厌恶的电影！”（大笑）<br><br>然后第二天我来到工作室，又看了一遍这部电影，然后想：“等等！或许也没那么糟糕？”（大笑）接着我又看了一遍然后：“不，这就是垃圾！”我总是在重复这个过程。
          </div>
        </div>

        <div class="flex gap-2">
          <div class="dialog-l">
            我也是只有当一个游戏最终完成的时候才会感到安心。
          </div>
        </div>

        <div class="flex gap-2 justify-end">
          <div class="dialog-r">
            当我拍电影的时候，我倾向于忘记我在已经做过的那些东西。但是我想做却还没有做的东西会仿佛我欠它们的一样，重重地压在我的肩头。当一部电影完成的时候我总是处于这样的状态，然后我会带着这种心态去参加各种采访。这对你的心理健康完全没有好处（大笑）。<br><br>我意识到，当我拍电影的时候，我从来不考虑观众，或者考虑如何吸引他们去电影院。我永远只考虑拍一部让我能满意的电影，我拍电影只为了让我自己有解脱的感觉。
          </div>
        </div>

        <div class="flex gap-2">
          <div class="dialog-l">
            在这方面，我要谢谢我的同事们。当我不知道何去何从的时候，其他人会替我去考虑这个问题（大笑）。当一切都完成的时候，他们会问：“你一开始就计划好了这一切吗？”但说实话，我真的不知道。<br><br>有时候，我真的不知道我们最终会走到哪里。这更像是：“这么做不是很有趣吗？那我们就这样做！”总是跟着我的直觉走，所以有时会失控。这听起来像是一个借口，但最近我会开始想，这种混乱也是游戏开发乐趣的一环，并且会为游戏增加更多的乐趣。<br><br>我认为，人们想要在动画和游戏中获得的东西是不同的。电子游戏是一种工具，就像是自行车或者立体声录放机。只是我们都碰巧使用了电视、剧本和画面，因此人们就认为游戏和电影或是小说是同一种产品。我承认，有一定程度的相似性，但电影你只能看，即使质量没那么好，人们也会不知怎么地就接受它。而如果这是电子游戏，用户很快就会感觉到无聊。
          </div>
        </div>

        <div class="flex gap-2 justify-end">
          <div class="dialog-r">
            我自己不怎么玩游戏，但我有时候会站在我儿子后面看他玩。我会倾向于为我儿子正在打的坏人加油（大笑）。
          </div>
        </div>

        <div class="flex gap-2">
          <div class="dialog-l">这才是享受电子游戏的正确方式（大笑）。</div>
        </div>

        <div class="flex gap-2 justify-end">
          <div class="dialog-r">
            我对自己玩游戏没什么兴趣，即使我玩，我也很快会输掉。但是我能分析出当前的状况，比如现在我很危险，或者如果我跟这个敌人战斗我就会死，或者别的什么。但就算我能选择一条正确的路逃出生天，我也通常不会获得什么快感。
          </div>
        </div>

        <div class="flex gap-2">
          <div class="dialog-l">我明白你的意思。</div>
        </div>

        <div class="flex gap-2 justify-end">
          <div class="dialog-r">
            我认为电子游戏和戏剧有一个本质的区别。如果这是戏剧，角色不一定就会选择正确的道路。他们经常会去尝试做一些不可能成功的事，即使他们知道自己毫无机会……但是之后就会发生一些意料之外的事让他们莫名其妙地成功了。某种程度上说，制作一部戏剧就是如何编造一个精彩的令人信服的谎言。<br><br>在红猪里，进行了一场狗斗之后，两个飞行员都安然无恙地离开，最后开始用拳头决胜负。我知道这与现实相去甚远。这也和电子游戏完全不同。所以我认为喜欢电子游戏的人根本不会拍电影。从某些方面来讲，电影比电子游戏百花齐放多了。
          </div>
        </div>

        <div class="flex gap-2">
          <div class="dialog-l">
            我不这么认为。我相信现在的电子游戏可能像你描述的那样。到如果我们能突破机能的限制，我们就可以制作像电影一样的游戏。如果我们把我们现在正在尝试制作的游戏发展好了，可能我们能制作一部能让我们的用户欣赏超过30小时的电子小说或是交互电影。
          </div>
        </div>

        <div class="flex gap-2 justify-end">
          <div class="dialog-r">
            有人曾经告诉我，你能在游戏里做很多事情。我对游戏没什么深入了解，但我心平气和地说起了我曾经想做的一个游戏……这是一个关于二战期间日军的故事。<br><br>它发生在日军在南太平洋上几乎快被美军全灭的时候。这个游戏的目标是登上一架三座鱼雷轰炸机并且用鱼雷击沉一艘美国航母。也就是说，你也可以选择不登上这架轰炸机。然后你会怎么做？<br><br>可能你会去一个岛上种菜来自给自足。也有可能最终战争结束，但你也会饿死。或者你可能会成为战俘，呆在监狱里直到战争结束。又或者你在整个过程开始的时候就死了。
          </div>
        </div>

        <div class="flex gap-2">
          <div class="dialog-l">我知道了。</div>
        </div>

        <div class="flex gap-2 justify-end">
          <div class="dialog-r">
            所以你能做很多选择，你能在你的鱼雷攻击航母之前检查它，以确保它的撞针能被正常激活。如果你不检查，你就不能发射鱼雷或者类似的东西。或者可能有敌人的战斗机飞过。所以你要怎么办？在云上飞还是云下飞？当你坐在三座轰炸机上的时候，后座的人就是机枪手。你在游戏开始时就有47发子弹并且已经打了30发。你接下来是要马上装填还是之后再说？<br><br>我们会制作所有的这些动画场景，然后你需要在5到10个计时器指示灯亮起前做出你的选择。我曾经讨论制作这样的游戏。
          </div>
        </div>

        <div class="flex gap-2">
          <div class="dialog-l">我知道了。</div>
        </div>

        <div class="flex gap-2 justify-end">
          <div class="dialog-r">
            我不知道我们如果要做一部这样的游戏需要多少光盘。但无论如何，即使有人说：“好！让我们来做这个游戏！”我也不认为我们能完成它。<br><br>动画师会厌倦，因为他们需要一次又一次地重绘差不多的镜头。我能想象他们最终会一个接一个地退出。动画师是人而不是机器。我觉得我们在创作的时候要考虑这一点。
          </div>
        </div>

        <div class="flex gap-2">
          <div class="dialog-l">
            最近，人们经常要求制作这样的游戏，我认为制作这样的游戏是可能的。当然喜欢电子游戏的创作者们希望走在正确的方向上，但他们也会渴望挑战。<br><br>当我看电影时，我经常会觉得事情进展得太过顺利了，这也太容易了。所以如果我能在现在的游戏和电影之间找到一个合适的中间地带，就能做出一个有趣的游戏。
          </div>
        </div>

        <div class="flex gap-2 justify-end">
          <div class="dialog-r">
            举个例子，当我开始画《阿尔卑斯山的少女》中的房子的时候，我会事先在脑海中构建一个模糊的房子的印象。然后，我开始从前门的角度画它。如果你进到这间房子里，壁炉在这里，椅子在那里……我画这些东西是基于我脑海中的印象的。<br><br>但为了戏剧张力，有时我们会从一个意想不到的角度来画房子，比如从房子的后面。然后我就想：“等等！它从后面看会是啥样来着？”（大笑）<br><br>当这样的情况发生的时候，你需要做的不是强行在这里编造什么东西，而是想象你在这个环境中，然后在房子里走来走去。接着你自然会得到一个视觉图像。<br><br>我认为这些图像会是你过去所看过东西的记忆碎片。所以它不是完全由你原创的。某种程度上讲，你正在描绘你之前在某处见过的东西。所以我总会感到：“我脑子里的图像总比我现在画的好，我画的看起来不好是因为我不善于描绘我脑中的图像。”
          </div>
        </div>

        <div class="flex gap-2">
          <div class="dialog-l">
            你可以用电脑来处理啊……如果你使用现代科技，你甚至不再需要人类的接触就能画东西。
          </div>
        </div>

        <div class="flex gap-2 justify-end">
          <div class="dialog-r">有时候我就在想，我是否应该这样去做。</div>
        </div>

        <div class="flex gap-2">
          <div class="dialog-l">
            <div class="flex items-center">
              <img src="./images/game.jpg" class="h-24 mb-4" />
            </div>
            一款名为第七访客的电脑游戏将在今年秋季发售。这游戏的开发者们买了一栋老房子并把整个房子都扫描进了电脑，只为了建立它的3D渲染图形数据。
          </div>
        </div>

        <div class="flex gap-2 justify-end">
          <div class="dialog-r">我其实也想过类似的事。</div>
        </div>

        <div class="flex gap-2">
          <div class="dialog-l">
            一旦你有了图形数据，你只需要在电脑上使用它。如果你想上楼，你就能上楼。你能非常快地看到行为的结果，因为和动画不同，你不需要把你去的所有地方都事无巨细地画一遍。<br><br>你只需要构建一个虚拟的环境，然后把它提供给用户。“在这个虚拟的环境中我们要做些什么？”这就是我们现在所想的事。
          </div>
        </div>

        <div class="flex gap-2 justify-end">
          <div class="dialog-r">想必这图形的数据量一定很巨大。</div>
        </div>

        <div class="flex gap-2">
          <div class="dialog-l">
            大概花了2年时间吧……他们自称只用了半年，但我知道他们肯定用了一年以上。这肯定需要花费时间，但是至少从技术角度来说这不再是不可能的了。<br><br>如果你想想在这样的环境下创造许多事件……那可太令人兴奋了。基本上你甚至可以看到电影里通常不会去展示的地方。我对这项新技术所能带来的可能性非常感兴趣。
          </div>
        </div>

        <div class="flex gap-2 justify-end">
          <div class="dialog-r">
            当我想到要做一个虚构的环境的时候，我通常会想知道风景是什么样的。如果有一个山坡，它不仅会包含听觉和视觉的信息，它还会包含有气味，当你走在上面时你的脚的触感，以及你的记忆中相似的地方。<br><br>风景是这些信息的集合体。<br><br>所以当我画一个山坡的时候，我试图也传达出这些感觉。某种程度上说，你能否做到这一点决定了你是否是一个优秀的动画师。我们叫它“空气感”（译者注：原来这就是塞尔达空气感的起源），并且这会是动画师的动画师的必备技能。也许你能把同样的事告诉游戏创作者。
          </div>
        </div>

        <div class="flex gap-2">
          <div class="dialog-l">
            我完全能理解你刚才所说的。如果能让用户感受到物体的触感，甚至感受到温度，那么用户就会真正地沉浸在环境当中。它基本上是关于如何只用听觉和视觉信息来激发用户的五感。<br><br>也就是说，我认为写在电子游戏中更容易实现，因为电子游戏更具交互性。用户能控制他们的角色。尤其是当今，我们能用采样器创建音乐或声效，这也有助于去激发用户的五感。所以也许电子游戏是比电影更有趣的媒体。
          </div>
        </div>

        <div class="flex gap-2 justify-end">
          <div class="dialog-r">
            我经常想知道，如何才能用一台相机去捕捉一棵树的本质。我在我的脑中进行了许多的模拟。我在我的脑中已经进行了模拟游戏了所以我不需要玩电子游戏了（大笑）。
          </div>
        </div>

        <div class="flex gap-2">
          <div class="dialog-l">哇，真的吗？</div>
        </div>

        <div class="flex gap-2 justify-end">
          <div class="dialog-r">
            树根是如何汲取水分的，水是如何在其他上流动的。风景中树的图像。树在不同季节时的样子……有时一个人会到这棵树下避雨。一只鸟会飞到这棵树上然后在树上死去。这棵树在空中的鸟儿眼中又是什么样的呢？<br><br>我经常在想，如果你能自由地移动相机并捕捉到所有的这一切，你能创造出什么样的照片呢？
          </div>
        </div>

        <div class="flex gap-2">
          <div class="dialog-l">
            如果你使用电脑，你就能做到这点。在《第七访客》，你甚至能将你的相机移动到吊灯的上方然后通过吊灯从上方看着自己。这非常有趣。
          </div>
        </div>

        <div class="flex gap-2 justify-end">
          <div class="dialog-r">
            但是除非你捕捉到风、季节和宇宙的运行，否则它都不会是真正的风景。我想我可能会对“天上飘浮着什么样的云彩”这样的事更感兴趣。<br><br>除非你拍到所有森罗万象，否则我不感觉不到世界是真实的。但我猜，如果你真的这样去做那数据量将是空前的。
          </div>
        </div>

        <div class="mt-2 mb-4 border-4 border-white shadow-xl">
          <img src="./images/newspaper.jpg" class="brightness-90" />
        </div>
      </section>

      <div class="px-4 w-full lg:hidden">
        <div
          class="h-[2px] w-full border-b border-[#f2ebe3] border-dashed"
        ></div>
      </div>

      <div class="px-4 pt-4 pb-8 lg:hidden flex">
        <div class="lg:hidden flex flex-col gap-2 py-4">
          <p
            class="p-1 bg-black/70 flex justify-center text-white rounded-lg w-10 text-xs"
          >
            补充
          </p>
          <div class="flex note gap-2">
            <div>1.</div>
            <div>
              译者注：这篇文章没有标题党，真的是宫本茂VS宫崎骏，两人观点的激烈碰撞让场面一度失控。然后就是宫崎骏的单方面输出和宫本茂的答不上来。然而大师始终是大师，在这样的观点交锋中，宫本茂竟然学到了宫崎骏创作哲学的真谛，并且学以致用，创造了塞尔达开发者们奋斗一生的“空气感”。
            </div>
          </div>
          <div class="flex note gap-2">
            <div>2.</div>
            <div>
              原文地址：<a
                href="https://www.bilibili.com/read/cv24202714/?spm_id_from=333.1007.0.0"
                >https://www.bilibili.com/read/cv24202714/?spm_id_from=333.1007.0.0</a
              >
            </div>
          </div>
          <div class="flex note gap-2">
            <div>3.</div>
            <div>
              电影简介：<a href="https://movie.douban.com/subject/1291838/"
                >https://movie.douban.com/subject/1291838/</a
              >
            </div>
          </div>
        </div>
      </div>
    </div>

    <footer
      class="fixed bottom-0 w-full px-10 h-6 flex items-center justify-between border-t bg-[#fff9f1] border-[#f2ebe3]"
    >
    <p class="info">Design & Develop by <a href="https://bluepika.life/about" class=" no-underline hover:underline">Bluepikachu</a></p>
    <p class="info"><a href="https://github.com/bluepikachu/porco-rossohttps://github.com/bluepikachu/porco-rosso" class=" no-underline hover:underline">GitHub</a></p>
    </footer>
  </section>
</template>

<style>
html {
  background-color: #fff9f1;
}

body {
  background-color: #fff9f1;
}
</style>
