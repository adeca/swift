add_swift_library(swiftGameplayKit IS_SDK_OVERLAY
  GameplayKit.swift
  GameplayKit.mm

  TARGET_SDKS OSX IOS IOS_SIMULATOR TVOS TVOS_SIMULATOR
  SWIFT_MODULE_DEPENDS Foundation simd GLKit SpriteKit
  FRAMEWORK_DEPENDS_WEAK GameplayKit)
