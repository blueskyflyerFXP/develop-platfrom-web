<template>
  <el-card class="box-card">
    <div slot="header" class="clearfix">
      <span style="font-weight: bold;font-size: 20px">项目进度</span>
      <!--<el-button style="float: right; padding: 3px 0" type="text">修改</el-button>-->
    </div>
    <div class="block">
      <el-timeline>
        <el-timeline-item timestamp="2021/1/10" placement="top">
          <el-card>
            <h4>向老师提交初步的项目框架和思考</h4>
            <p>凡兴鹏 提交于 2021年1月10日</p>
            <p>完成度：基本完成</p>
          </el-card>
        </el-timeline-item>
        <el-timeline-item timestamp="2021/3/7" placement="top">
          <el-card>
            <h4>提交初步任务书和选题</h4>
            <p>凡兴鹏 提交于 2021年3月7日</p>
            <p>完成度：基本完成</p>
          </el-card>
        </el-timeline-item>
        <el-timeline-item timestamp="2021/3/29" placement="top">
          <el-card>
            <h4>开始项目设计和框架选型</h4>
            <p>凡兴鹏 提交于 2021年3月29日</p>
            <p>完成度：基本完成</p>
          </el-card>
        </el-timeline-item>
        <el-timeline-item timestamp="2021/4/3" placement="top">
          <el-card>
            <h4>搭建项目并编写基础工具类</h4>
            <p>凡兴鹏 提交于 2021年4月3日</p>
            <p>完成度：基本完成</p>
          </el-card>
        </el-timeline-item>
        <el-timeline-item timestamp="2021/4/7" placement="top">
          <el-card>
            <h4>进行框架调试和工具类的调试</h4>
            <p>凡兴鹏 提交于 2021年4月7日</p>
            <p>完成度：基本完成</p>
          </el-card>
        </el-timeline-item>
        <el-timeline-item timestamp="2021/4/9" placement="top">
          <el-card>
            <h4>工具类实现扫描包下的类和属性，进行代码风格检查和通过实体类自动生成表结构</h4>
            <p>凡兴鹏 提交于 2021年4月9日</p>
            <p>完成度：基本完成</p>
          </el-card>
        </el-timeline-item>
        <el-timeline-item timestamp="2021/4/15" placement="top">
          <el-card>
            <h4>编写后端，使用mybatis和mysql，实现登录和注册功能</h4>
            <p>凡兴鹏 提交于 2021年4月15日</p>
            <p>完成度：基本完成</p>
          </el-card>
        </el-timeline-item>
        <el-timeline-item timestamp="2021/4/18" placement="top">
          <el-card>
            <h4>项目加入用户管理、用户注册和角色管理模块</h4>
            <p>凡兴鹏 提交于 2021年4月18日</p>
            <p>完成度：基本完成</p>
          </el-card>
        </el-timeline-item>
        <el-timeline-item timestamp="2021/4/20" placement="top">
          <el-card>
            <h4>编写笔记模块，实现随时记录自己的想法</h4>
            <p>凡兴鹏 提交于 2021年4月20日</p>
            <p>完成度：基本完成</p>
          </el-card>
        </el-timeline-item>
        <el-timeline-item timestamp="2021/4/23" placement="top">
          <el-card>
            <h4>加入图书展示模块并对界面进行优化</h4>
            <p>凡兴鹏 提交于 2021年4月23日</p>
            <p>完成度：基本完成</p>
          </el-card>
        </el-timeline-item>
        <el-timeline-item timestamp="2021/4/25" placement="top">
          <el-card>
            <h4>后台增加图书管理和内容管理（意图增加首页的广告管理）</h4>
            <p>凡兴鹏 提交于 2021年4月25日</p>
            <p>完成度：基本完成</p>
          </el-card>
        </el-timeline-item>
        <el-timeline-item timestamp="2021/4/28" placement="top">
          <el-card>
            <h4>后台进行基本Vue组件的页面展示</h4>
            <p>凡兴鹏 提交于 2021年4月28日</p>
            <p>完成度：基本完成</p>
          </el-card>
        </el-timeline-item>
        <el-timeline-item timestamp="2019/5/2" placement="top">
          <el-card>
            <h4>调试首页、笔记、图书和后台的逻辑，修复部分Bug</h4>
            <p>凡兴鹏 提交于 2021年5月5日</p>
            <p>完成度：未完成</p>
          </el-card>
        </el-timeline-item>
      </el-timeline>
    </div>
  </el-card>
</template>

<script>
  export default {
    name: 'UpdateCard'
  }
</script>

<style scoped>
  .box-card {
    margin-top: 5px;
    width: 988px;
    height: 3000px;
    text-align: left;
  }
</style>
