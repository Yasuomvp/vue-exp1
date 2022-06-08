<template>
  <el-row>
    <el-col :span="3">
      <el-menu
          default-active="2"
          class="el-menu-vertical-demo"
      >

        <router-link to="/path1">
          <el-menu-item index="1">
            <el-icon>
              <icon-menu/>
            </el-icon>
            <span>导航1</span>
          </el-menu-item>
        </router-link>

        <router-link to="/path2">
          <el-menu-item index="2">
            <el-icon>
              <document/>
            </el-icon>
            <span>导航2</span>
          </el-menu-item>
        </router-link>
      </el-menu>
    </el-col>
    <el-col :span="21">
      <router-view></router-view>
    </el-col>
  </el-row>
</template>