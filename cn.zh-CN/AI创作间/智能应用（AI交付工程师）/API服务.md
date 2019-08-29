# API服务 {#task_1357704 .task}

算法运行完成后，会生成相应的API，您可以通过在开发项目中配置API对应的serviceId，并下载SDK开发包，使用Open API来调用该API服务。

1.  进入AI创作间的智能应用页面，单击**API服务**，进入**API服务**页面。![API服务页面](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/1082248/156706572053074_zh-CN.png)

 该页面包括两部分，左侧为API列表页，右侧为API的详情展示页，功能说明如下。
    -   API列表页：展示了算法相关的API。
    -   API的详情展示页：展示了API的详细信息，包括**参数配置**、**请求参数**、**返回参数**、**正常返回示例**及**错误码定义**。您可以在该页面获取API的serviceId，配置到您的程序中进行调用。
2.  发布API。 
    1.  在**算法相关API**下，选择您要发布的算法API，单击右侧的**发布**（![发布](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/1082248/156706572053076_zh-CN.png)）图标。
    2.  在API发布弹出框中选择算法的**版本号**和需要覆盖的数据单击**下一步**。![API发布页面](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/1082248/156706572053077_zh-CN.png)


    3.  确认后，单击**发布**。
    4.  发布成功后，系统会提示**发布成功**，且**发布**图标切换为下线（![下线](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/1082248/156706572053078_zh-CN.png)）图标。![算法相关API](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/1082248/156706572053079_zh-CN.png)


3.  下载SDK。 在左侧API列表中选择一个API，单击页面右上角的**下载SDK**。在**下载SDK**页面，单击选择您的开发语言，下载该API的SDK开发包。下载完成后，可参考[API调用方式](https://help.aliyun.com/document_detail/101110.html)进行调用。目前工业大脑支持五种开发语言，如下图所示。

    ![下载SDK页面](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/1082248/156706572053080_zh-CN.png)

4.  下线API。 在**算法相关API**下，选择您要下线的算法API，单击右侧的**下线**（![下线](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/1082248/156706572053078_zh-CN.png)）图标。

    **说明：** 

    -   API下线后，会导致程序调用失败，再次上线后可恢复，请谨慎操作。
    -   API下线后，才可在项目清单页面删除对应的项目。

