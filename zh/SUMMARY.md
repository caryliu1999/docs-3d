# Summary

## 新手入门

[介绍](index.md)

- [启动](getting-started/index.md)
  - [Dashboard](getting-started/dashboard/index.md)
  - [Hello world!](getting-started/helloworld/index.md)
  - [快速上手：制作第一个游戏](getting-started/first-game/index.md)
  - [注意事项](getting-started/attention/index.md)

## 编辑器手册

- [面板介绍](editor/index.md)
  - [场景编辑器](editor/scene/index.md)
  - [层级管理器](editor/hierarchy/index.md)
  - [资源管理器](editor/assets/index.md)
  - [属性检查器](editor/inspector/index.md)
  - [控制台](editor/console/index.md)
  - [动画编辑器](editor/animation/index.md)
  - [偏好设置](editor/preferences/index.md)
  - [项目设置](editor/project/index.md)
  - [引擎定制工作流程](editor/engine-customization/engine-customization.md)

- [项目预览调试](editor/preview/index.md)
  - [浏览器预览](editor/preview/browser.md)
  - [预览流程简介与常见错误处理](preview-guid.md)

- [粒子编辑器](particle-system/editor/index.md)
  - [曲线编辑器](particle-system/editor/curve-editor.md)
  - [渐变色编辑器](particle-system/editor/gradient-editor.md)
  - [控制面板](particle-system/editor/particle-effect-panel.md)

- [动画系统](editor/animation/index.md)
  - [关于 Animation](editor/animation/animation.md)
  - [熟悉动画编辑器](editor/animation/animation-editor.md)
  - [创建 Animation 组件和动画剪辑](editor/animation/animation-create.md)
  - [编辑动画序列](editor/animation/animation-clip.md)
  - [编辑帧动画](editor/animation/sprite-animation.md)
  - [编辑动画曲线](editor/animation/animation-curve.md)
  - [动画事件](editor/animation/animation-event.md)
- [地形系统](editor/terrain/index.md)

- [构建发布](editor/publish/index.md)
  - [熟悉构建发布面板](editor/publish/build-panel.md)
  - [通用构建参数介绍](editor/publish/build-options.md)
  - [发布到 web 平台](editor/publish/publish-web.md)
  - [发布到微信小游戏](editor/publish/publish-wechatgame.md)
    - [接入微信小游戏的开放数据域](editor/publish/publish-wechatgame-subcontext.md)
    - [启用微信小游戏引擎插件](editor/publish/wechatgame-plugin.md)
  - [发布到原生平台](editor/publish/publish-native.md)
    - [安装配置原生环境](editor/publish/setup-native-development.md)
    - [原生平台 JavaScript 调试](editor/publish/debug-jsb.md)
  - [发布到 OPPO 小游戏](editor/publish/publish-oppo-mini-game.md)
  - [发布到华为小游戏](editor/publish/publish-huawei-mini-game.md)
  - [发布到 vivo 小游戏](editor/publish/publish-vivo-mini-game.md)
  - [发布到小米快游戏](editor/publish/publish-xiaomi-quick-game.md)
  - [发布到 Cocos Play](editor/publish/publish-cocos-play.md)
  - [发布到支付宝小游戏](editor/publish/publish-alipay-mini-game.md)
  - [命令行发布项目](editor/publish/publish-in-command-line.md)
  - [定制项目的构建模版](editor/publish/custom-project-build-template.md)
  - [构建流程简介与常见错误处理](editor/publish/build-guide.md)

## 引擎手册

- [功能地图](module-map/index.md)
  - [图形渲染](module-map/graphics.md)

- [场景及环境](concepts/scene/index.md)
  - [坐标系](concepts/scene/coord.md)
  - [场景结构](concepts/scene/scene.md)
  - [节点](concepts/scene/node.md)
  - [天空盒](concepts/scene/skybox.md)

- [光照](concepts/scene/light.md)
  - [基于物理的光照](concepts/scene/light/pbr-lighting.md)
  - [主方向光](concepts/scene/light/dir-light.md)
  - [球面光](concepts/scene/light/sphere-light.md)
  - [聚光灯](concepts/scene/light/spot-light.md)
  - [阴影](concepts/scene/shadow.md)
  - [环境光](concepts/scene/ambient.md)

- [材质](material-system/overview.md)
  - [YAML 101](material-system/yaml-101.md)
  - [Effect Syntax](material-system/effect-syntax.md)
  - [Pass Params](material-system/pass-parameter-list.md)
  - [Builtin Shader Uniforms](material-system/builtin-shader-uniforms.md)

- [声音](audio-system/overview.md)

- [粒子](particle-system/overview.md)
  - [粒子系统模块](particle-system/module.md)
  - [主模块(ParticleSystemComponent)](particle-system/main-module.md)
  - [发射器模块(ShapeModule)](particle-system/emitter.md)
  - [颜色模块(ColorOvertimeModule)](particle-system/color-module.md)
  - [大小模块(SizeOvertimeModule)](particle-system/size-module.md)
  - [旋转模块(RotationOvertimeModule)](particle-system/rotation-module.md)
  - [速度模块(VelocityOvertimeModule)](particle-system/velocity-module.md)
  - [限速模块(LimitVelocityOvertimeModule)](particle-system/limit-velocity-module.md)
  - [加速度模块(ForceOvertimeModule)](particle-system/force-module.md)
  - [贴图动画模块(TextureAnimationModule)](particle-system/texture-animation-module.md)
  - [渲染模块(Renderer)](particle-system/renderer.md)
  - [拖尾模块(TrailModule)](particle-system/trail-module.md)

- [动画](engine/animation/index.md)
  - [动画组件](engine/animation/animation-component.md)
  - [动画剪辑](engine/animation/animation-clip.md)
  - [骨骼动画](engine/animation/skeletal-animation.md)
- [缓动](tween/index.md)

- [物理](physics/physics.md)
  - [物理选项](physics/physics-item.md)
  - [物理系统](physics/physics-system.md)
  - [物理组件](physics/physics-component.md)
  - [物理使用](physics/physics-use.md)
  - [使用碰撞体](physics/physics-collider.md)
  - [物理材质](physics/physics-material.md)
  - [使用刚体](physics/physics-rigidbody.md)
  - [物理事件](physics/physics-event.md)
  - [分组和掩码](physics/physics-group-mask.md)
  - [射线检测](physics/physics-raycast.md)

- [UI](ui-system/components/engine/index.md)
  - [渲染排序规则](ui-system/components/engine/priority.md)
  - [UI合批说明](ui-system/components/engine/ui-batch.md)
  - [多分辨率适配方案](ui-system/components/engine/multi-resolution.md)
  - [对齐策略](ui-system/components/engine/widget-align.md)
  - [文字排版](ui-system/components/engine/label-layout.md)
  - [自动布局容器](ui-system/components/engine/auto-layout.md)
  - [制作动态生成内容的列表](ui-system/components/engine/list-with-data.md)
  - [制作可任意拉伸的 UI 图像](ui-system/components/engine/sliced-sprite.md)

- [组件](editor/components/index.md)
  - [AudioSourceComponent](audio-system/overview.md)
  - [ModelComponent](engine/renderable/model-component.md)
  - [SkinningModelComponent](engine/animation/skeletal-animation.md)
  - [CameraComponent](editor/components/camera-component.md)
  - [DirectionalLightComponent](concepts/scene/light/dir-light.md)
  - [SphereLightComponent](concepts/scene/light/sphere-light.md)
  - [SpotLightComponent](concepts/scene/light/spot-light.md)
  - [AnimationComponent](engine/animation/animation-component.md)
  - [BillboardComponent](particle-system/billboard-component.md)
  - [LineComponent](particle-system/line-component.md)
  - [ParticleSystemComponent](particle-system/main-module.md)
  - [BoxColliderComponent](physics/physics-component.md#盒碰撞器组件（boxcollidercomponent）)
  - [SphereColliderComponent](physics/physics-component.md#球碰撞器组件（spherecollidercomponent）)
  - [RigidBodyComponent](physics/physics-component.md#刚体组件)
  - [UI 组件](ui-system/components/editor/index.md)
    - [UI 渲染组件](ui-system/components/editor/render-component.md)
      - [SpriteComponent 参考](ui-system/components/editor/sprite.md)
      - [LabelComponent 参考](ui-system/components/editor/label.md)
      - [MaskComponent 参考](ui-system/components/editor/mask.md)
      - [LabelOutlineComponent 参考](ui-system/components/editor/label-outline.md)
      - [GraphicsComponent 参考](ui-system/components/editor/graphics.md)
      - [RichTextComponent 参考](ui-system/components/editor/richtext.md)
    - [UI 基础组件](ui-system/components/editor/base-component.md)
      - [CanvasComponent 参考](ui-system/components/editor/canvas.md)
      - [UIReorderComponent 参考](ui-system/components/editor/ui-reorder-component.md)
      - [UITransformComponent 参考](ui-system/components/editor/ui-transform.md)
      - [WidgetComponent 参考](ui-system/components/editor/widget.md)
      - [ButtonComponent 参考](ui-system/components/editor/button.md)
      - [LayoutComponent 组件参考](ui-system/components/editor/layout.md)
      - [EditBoxComponent 组件参考](ui-system/components/editor/editbox.md)
      - [ScrollViewComponent 组件参考](ui-system/components/editor/scrollview.md)
      - [ScrollBarComponent 组件参考](ui-system/components/editor/scrollbar.md)
      - [ProgressBarComponent 组件参考](ui-system/components/editor/progress.md)
      - [ToggleComponent 组件参考](ui-system/components/editor/toggle.md)
      - [ToggleContainerComponent 组件参考](ui-system/components/editor/toggleContainer.md)
      - [SliderComponent 组件参考](ui-system/components/editor/slider.md)
      - [PageViewComponent 组件参考](ui-system/components/editor/pageview.md)
      - [PageViewIndicatorComponent 组件参考](ui-system/components/editor/pageviewindicator.md)
      - [UIModelComponent 组件参考](ui-system/components/editor/ui-model.md)
      - [UIStaticComponent 组件参考](ui-system/components/editor/ui-static.md)
      - [UICoordinateTracker 组件参考](ui-system/components/editor/ui-coordinate-tracker.md)
      - [UIOpacity 组件参考](ui-system/components/editor/ui-opacity.md)

- [脚本指南及事件机制](scripting/index.md)
  - [脚本创建](scripting/setup.md)
  - [脚本基础](scripting/basic.md)
  - [语言支持](scripting/language-support.md)
  - [ccclass](scripting/ccclass.md)
  - [属性参数参考](scripting/reference/attributes.md)
  - [访问节点和其他组件](scripting/access-node-component.md)
  - [常用节点和组件接口](scripting/basic-node-api.md)
  - [生命周期回调](scripting/life-cycle-callbacks.md)
  - [创建和销毁节点](scripting/create-destroy.md)
  - [加载和切换场景](scripting/scene-managing.md)
  - [获取和加载资源](scripting/load-assets.md)
  - [使用计时器](scripting/scheduler.md)
  - [组件](scripting/component.md)
  - [组件顺序](scripting/execution-order-component.md)
  - [事件机制](engine/event/index.md)
  - [插件脚本](scripting/plugin-scripts.md)
  - [添加 Log](scripting/log.md)
  - [废弃 API](scripting/deprecated.md)

- [资源手册](asset/index.md)
  - [资源工作流](asset/asset-workflow.md)
  - [获取和加载资源](asset/load-assets.md)
  - [分包加载](asset/subpackage.md)
  - [场景资源](asset/scene.md)
  - [图像资源](asset/image.md)
    - [纹理贴图资源](asset/texture.md)
    - [精灵帧资源](asset/sprite-frame.md)
    - [立方体贴图资源](concepts/scene/skybox.md#cubemap)
    - [图像资源的自动裁剪](ui-system/components/engine/trim.md)
    - [压缩纹理](asset/compress-texture.md)
    - [图集资源](asset/atlas.md)
    - [自动图集资源](asset/auto-atlas.md)
    - [渲染纹理](asset/render-texture.md)
  - [预制资源](asset/prefab.md)
  - [脚本资源](asset/script.md)
  - [字体资源](asset/font.md)
  - [声音资源](asset/audio.md)
  - [材质资源](asset/material.md)
  - [模型资源](asset/mesh.md)
  - [动画资源](asset/anim.md)
- [向Cocos提交代码](submit-pr/submit-pr.md)
