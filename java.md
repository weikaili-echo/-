#1.软件测试就是利用测试工具按照测试方案和流程对产品进行功能和性能测试，甚至根据需要编写不同的测试工具，设计和维护测试系统，对测试方案可能出现的问题进
行分析和评估。
##2.为了节省后期修改BUG的成本，所以要在程序研发阶段就引入软件测试，这样可以从源头上发现bug、解决bug，从而有效的提高软件质量 ，减少后期的维护成本。
##3.编写测试用例，可以避免测试点的遗漏。
##4.有时候需求是一点点来的，不是很系统，测试用例及时更新，可以作为系统的需求。
##5.帮助编写人员编写代码，也可以为代码的补充提供保障，只要重组代码之后单元测试全部运行通过，那么在相应的表示此替换没有约会的新的BUG，当然这是建立在完整，
有效的单元测试覆盖率的基础上。


### Java
int a [] = new int [5];
系统。出来。println（“请输入任意六个整数：”）;
Scanner hehe = new Scanner（System。in）;
for（int b = 0; b <s.length; b ++）
        a [b] -hehe.nextInt（）;
for（int i = 1; i <5; i ++）
{
        for（int j = i; j> 0; j--）
        {
              如果（s [j]> s [j-1]）
        {int temp;
            temp = s [j];
            s [j] = s [j-1];
            s [j-1] = temp;
         }
}

##测试用例
+第一：0,1,2,3,4,5,6,7,8,9
+第二：9,8,7,6,5,4,3,2,1,0
+第三：5,6,7,1,2,3,8,0,9,4
+第四：7,5,6,3,2,8,0,9,4,1
