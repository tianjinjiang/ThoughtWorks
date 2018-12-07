Conference Track Management
=================================

## 准备开发环境

### 下载项目代码

## 启动开发

要正常在本地运行本项目，需要启动三个控制台：

- Console 1
	- Ad Service 服务
- Console 2
	- Play 后端
- Console 3
	- NPM 前端

### 启动依赖项目

	# Console 1
	cd <ROOT>/ad-service
	sbt "run 9001"

### 启动 Play 后端

	# Console 2
	cd <ROOT>/operating-portal
	sbt "run 9000"

### 启动 前端

	# Console 3
	cd <ROOT>/portal-fe
	npm run dev

## Play Commands

`sbt run` Run Play application.
`sbt eclipse` Generate Eclipse project file.

## Yarn Commands

`yarn run build:dev` DEBUG build.
`yarn run build:prod` RELEASE build.
`yarn run start` Development mode with Webpack HMR.
