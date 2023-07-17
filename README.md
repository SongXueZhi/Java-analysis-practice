# Java-analysis-practice
以下t练习以项目代码为数据，例如regression库中的简单项目。注意练习中多使用现有库，保证代码风格和质量。
1. AST的访问。Java Parser 如何访问代码AST中的特定节点、并获得相应属性，例如方法声明节点获得方法名与signature，类声明节点....
2. Call Graph 和UD Pair（use-defination）。 使用Java Parser 给定一个测试方法获取测试方法Call Graph ，给定一个变量，例如断言中的变量，获取该变量的声明位置，以及变量类型。
3. AST的修改。使用Java Parser  给定一个类，尝试使用AST修改代码，例如把一个类中的某个方法的某一行删掉，再替换为别的代码。
4. * 前三个熟练后进入该练习。 了解java instrumentation的技术原理，使用ASM在bytecode级别插桩，记录一个demo project（由main 函数和几个简单调用方法组成）的方法粒度的执行trace。
