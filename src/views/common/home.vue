<template>
  <div class="mod-home">

    <h3>项目介绍</h3>
    <ul>
      <li>友好的代码结构及注释，便于阅读及二次开发。</li>
      <li>实现前后端分离，通过token进行数据交互。</li>
      <li>完善的代码生成机制，可在线生成po、xml、dao、service代码，减少50%以上的开发任务</li>
      <li>`lombok`使用，简化model类的get和set等生成方法.</li>
      <li>`Controller`使用`@RestController`接口返回json.</li>
      <li>`@Valid`控制参数限制。</li>
      <li>`@RequestBody`传入参。</li>
      <li>使用`@SysLogger`进行系统操作日志记录（切面实现）。</li>
      <li>统一异常返回处理。</li>
      <li>使用`tk.mybatis`简化MyBatis的框架代码。</li>
      <li>`shiro`安全框架使用，基于token的登录，认证等权限控制。</li>
      <li>灵活的权限控制，可控制到页面或按钮，满足绝大部分的权限需求。</li>
      <li>基于`BRAC`(基于角色访问控制)的安全架构设计。</li>
      <li>基于`swagger`实现在线后端接口文档。</li>
    </ul>

  </div>
</template>

<script>
  export default {
  }
</script>

<style>
  .mod-home {
    line-height: 1.5;
  }
</style>

