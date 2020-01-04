---
title: Java Reflection
categories:
  - Study
  - Java
date: 2020-01-04 20:23:54
tags:
---


(一) Java反射

反射是指程序在运行期可以拿到一个对象的所有信息。
反射是为了解决在运行期，对某个实例一无所知的情况下，如何调用其方法

{% codeblock 获取实例的方法 lang:java %}
import java.lang.reflection.*;
public static void main(String[] args){
	Class cls = String.class;
	Integer i = new Integer(123);
	Class intCls = i.getClass();
	}
{% endcodeblock %}




