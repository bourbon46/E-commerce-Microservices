# E-commerce Microservices Project

## 目录
1. [系统概述](#系统概述)
2. [架构图](#架构图)
3. [微服务详解](#微服务详解)
   - [Discovery Server](#discovery-server)
   - [Config Server](#config-server)
   - [API Gateway](#api-gateway)
   - [User Service](#user-service)
   - [Product Service](#product-service)
   - [Order Service](#order-service)
   - [Payment Service](#payment-service)
4. [横切关注点](#横切关注点)
   - [日志管理](#日志管理)
   - [认证和授权](#认证和授权)
   - [分布式追踪](#分布式追踪)
5. [如何运行项目](#如何运行项目)
6. [技术栈](#技术栈)

## 系统概述

本项目是一个基于微服务架构的电子商务系统。它由多个独立的服务组成，每个服务负责特定的业务功能。这种架构提高了系统的可扩展性、灵活性和可维护性。

主要特点：
- 服务发现与注册
- 集中式配置管理
- API 网关作为单一入口点
- 用户、产品、订单和支付的核心业务服务
- 分布式日志管理
- JWT 认证
- 分布式追踪

## 架构图

