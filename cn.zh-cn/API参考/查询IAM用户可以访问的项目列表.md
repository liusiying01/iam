# 查询IAM用户可以访问的项目列表<a name="iam_06_0003"></a>

## 功能介绍<a name="zh-cn_topic_0221482440_section135561150103812"></a>

该接口可以用于查询IAM用户可以访问的项目列表。

该接口可以使用全局区域的Endpoint和其他区域的Endpoint调用。IAM的Endpoint请参见：[地区和终端节点](https://developer.huaweicloud.com/endpoint?IAM)。

## 调试<a name="section55313301579"></a>

您可以在[API Explorer](https://apiexplorer.developer.huaweicloud.com/apiexplorer/doc?product=IAM&api=KeystoneListAuthProjects)中调试该接口。

## URI<a name="zh-cn_topic_0221482440_section5558135012383"></a>

GET /v3/auth/projects

## 请求参数<a name="zh-cn_topic_0221482440_section9559155010388"></a>

**表 1**  请求Header参数

<a name="zh-cn_topic_0221482440_HeaderParameter"></a>
<table><thead align="left"><tr id="zh-cn_topic_0221482440_row185601750153811"><th class="cellrowborder" valign="top" width="20%" id="mcps1.2.5.1.1"><p id="zh-cn_topic_0221482440_p756175033816"><a name="zh-cn_topic_0221482440_p756175033816"></a><a name="zh-cn_topic_0221482440_p756175033816"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="20%" id="mcps1.2.5.1.2"><p id="zh-cn_topic_0221482440_p956216508387"><a name="zh-cn_topic_0221482440_p956216508387"></a><a name="zh-cn_topic_0221482440_p956216508387"></a>是否必选</p>
</th>
<th class="cellrowborder" valign="top" width="10%" id="mcps1.2.5.1.3"><p id="zh-cn_topic_0221482440_p185625503388"><a name="zh-cn_topic_0221482440_p185625503388"></a><a name="zh-cn_topic_0221482440_p185625503388"></a>参数类型</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.2.5.1.4"><p id="zh-cn_topic_0221482440_p1356311502387"><a name="zh-cn_topic_0221482440_p1356311502387"></a><a name="zh-cn_topic_0221482440_p1356311502387"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="zh-cn_topic_0221482440_row9560350173819"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.5.1.1 "><p id="zh-cn_topic_0221482440_p3564125033816"><a name="zh-cn_topic_0221482440_p3564125033816"></a><a name="zh-cn_topic_0221482440_p3564125033816"></a>Content-Type</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.5.1.2 "><p id="zh-cn_topic_0221482440_p256510508389"><a name="zh-cn_topic_0221482440_p256510508389"></a><a name="zh-cn_topic_0221482440_p256510508389"></a>是</p>
</td>
<td class="cellrowborder" valign="top" width="10%" headers="mcps1.2.5.1.3 "><p id="zh-cn_topic_0221482440_p2565105043818"><a name="zh-cn_topic_0221482440_p2565105043818"></a><a name="zh-cn_topic_0221482440_p2565105043818"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.2.5.1.4 "><p id="zh-cn_topic_0221482440_p1156635014381"><a name="zh-cn_topic_0221482440_p1156635014381"></a><a name="zh-cn_topic_0221482440_p1156635014381"></a>该字段内容填为“application/json;charset=utf8”。</p>
</td>
</tr>
<tr id="zh-cn_topic_0221482440_row75601450163819"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.5.1.1 "><p id="zh-cn_topic_0221482440_p15567135014387"><a name="zh-cn_topic_0221482440_p15567135014387"></a><a name="zh-cn_topic_0221482440_p15567135014387"></a>X-Auth-Token</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.5.1.2 "><p id="zh-cn_topic_0221482440_p145676501385"><a name="zh-cn_topic_0221482440_p145676501385"></a><a name="zh-cn_topic_0221482440_p145676501385"></a>是</p>
</td>
<td class="cellrowborder" valign="top" width="10%" headers="mcps1.2.5.1.3 "><p id="zh-cn_topic_0221482440_p356810504385"><a name="zh-cn_topic_0221482440_p356810504385"></a><a name="zh-cn_topic_0221482440_p356810504385"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.2.5.1.4 "><p id="zh-cn_topic_0221482440_p35691350153818"><a name="zh-cn_topic_0221482440_p35691350153818"></a><a name="zh-cn_topic_0221482440_p35691350153818"></a>IAM用户的token（无需特殊权限）。</p>
</td>
</tr>
</tbody>
</table>

## 响应参数<a name="zh-cn_topic_0221482440_section35701050123815"></a>

**表 2**  响应Body参数

<a name="zh-cn_topic_0221482440_responseParameter"></a>
<table><thead align="left"><tr id="zh-cn_topic_0221482440_row1557145073819"><th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.1"><p id="zh-cn_topic_0221482440_p13572125014385"><a name="zh-cn_topic_0221482440_p13572125014385"></a><a name="zh-cn_topic_0221482440_p13572125014385"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.2"><p id="zh-cn_topic_0221482440_p157305053812"><a name="zh-cn_topic_0221482440_p157305053812"></a><a name="zh-cn_topic_0221482440_p157305053812"></a>参数类型</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.2.4.1.3"><p id="zh-cn_topic_0221482440_p9573195043812"><a name="zh-cn_topic_0221482440_p9573195043812"></a><a name="zh-cn_topic_0221482440_p9573195043812"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="zh-cn_topic_0221482440_row057165010389"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="zh-cn_topic_0221482440_p1157455019383"><a name="zh-cn_topic_0221482440_p1157455019383"></a><a name="zh-cn_topic_0221482440_p1157455019383"></a><a href="#zh-cn_topic_0221482440_response_Rs63Links">links</a></p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="zh-cn_topic_0221482440_p457511509388"><a name="zh-cn_topic_0221482440_p457511509388"></a><a name="zh-cn_topic_0221482440_p457511509388"></a>Object</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="zh-cn_topic_0221482440_p15575205043812"><a name="zh-cn_topic_0221482440_p15575205043812"></a><a name="zh-cn_topic_0221482440_p15575205043812"></a>资源链接信息。</p>
</td>
</tr>
<tr id="zh-cn_topic_0221482440_row557165013381"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="zh-cn_topic_0221482440_p1457610500383"><a name="zh-cn_topic_0221482440_p1457610500383"></a><a name="zh-cn_topic_0221482440_p1457610500383"></a><a href="#zh-cn_topic_0221482440_response_Rs63ProjectsArritem">projects</a></p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="zh-cn_topic_0221482440_p5577125018388"><a name="zh-cn_topic_0221482440_p5577125018388"></a><a name="zh-cn_topic_0221482440_p5577125018388"></a>Array of objects</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="zh-cn_topic_0221482440_p10578250173814"><a name="zh-cn_topic_0221482440_p10578250173814"></a><a name="zh-cn_topic_0221482440_p10578250173814"></a>项目信息列表。</p>
</td>
</tr>
</tbody>
</table>

**表 3**  links

<a name="zh-cn_topic_0221482440_response_Rs63Links"></a>
<table><thead align="left"><tr id="zh-cn_topic_0221482440_row11578165013810"><th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.1"><p id="zh-cn_topic_0221482440_p18579550123815"><a name="zh-cn_topic_0221482440_p18579550123815"></a><a name="zh-cn_topic_0221482440_p18579550123815"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.2"><p id="zh-cn_topic_0221482440_p1058015010381"><a name="zh-cn_topic_0221482440_p1058015010381"></a><a name="zh-cn_topic_0221482440_p1058015010381"></a>参数类型</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.2.4.1.3"><p id="zh-cn_topic_0221482440_p1258145016381"><a name="zh-cn_topic_0221482440_p1258145016381"></a><a name="zh-cn_topic_0221482440_p1258145016381"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="zh-cn_topic_0221482440_row457875015386"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="zh-cn_topic_0221482440_p55814505382"><a name="zh-cn_topic_0221482440_p55814505382"></a><a name="zh-cn_topic_0221482440_p55814505382"></a>self</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="zh-cn_topic_0221482440_p2058265017380"><a name="zh-cn_topic_0221482440_p2058265017380"></a><a name="zh-cn_topic_0221482440_p2058265017380"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="zh-cn_topic_0221482440_p1158375043817"><a name="zh-cn_topic_0221482440_p1158375043817"></a><a name="zh-cn_topic_0221482440_p1158375043817"></a>资源链接地址。</p>
</td>
</tr>
</tbody>
</table>

**表 4**  projects

<a name="zh-cn_topic_0221482440_response_Rs63ProjectsArritem"></a>
<table><thead align="left"><tr id="zh-cn_topic_0221482440_row85831050143820"><th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.1"><p id="zh-cn_topic_0221482440_p195843500381"><a name="zh-cn_topic_0221482440_p195843500381"></a><a name="zh-cn_topic_0221482440_p195843500381"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.2"><p id="zh-cn_topic_0221482440_p35856500386"><a name="zh-cn_topic_0221482440_p35856500386"></a><a name="zh-cn_topic_0221482440_p35856500386"></a>参数类型</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.2.4.1.3"><p id="zh-cn_topic_0221482440_p85861450183816"><a name="zh-cn_topic_0221482440_p85861450183816"></a><a name="zh-cn_topic_0221482440_p85861450183816"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="zh-cn_topic_0221482440_row135831650103818"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="zh-cn_topic_0221482440_p05871501386"><a name="zh-cn_topic_0221482440_p05871501386"></a><a name="zh-cn_topic_0221482440_p05871501386"></a>is_domain</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="zh-cn_topic_0221482440_p1058745023810"><a name="zh-cn_topic_0221482440_p1058745023810"></a><a name="zh-cn_topic_0221482440_p1058745023810"></a>Boolean</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="zh-cn_topic_0221482440_p14588165020389"><a name="zh-cn_topic_0221482440_p14588165020389"></a><a name="zh-cn_topic_0221482440_p14588165020389"></a>false.</p>
</td>
</tr>
<tr id="zh-cn_topic_0221482440_row12583650123812"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="zh-cn_topic_0221482440_p2058805019383"><a name="zh-cn_topic_0221482440_p2058805019383"></a><a name="zh-cn_topic_0221482440_p2058805019383"></a>description</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="zh-cn_topic_0221482440_p258985093819"><a name="zh-cn_topic_0221482440_p258985093819"></a><a name="zh-cn_topic_0221482440_p258985093819"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="zh-cn_topic_0221482440_p85905500385"><a name="zh-cn_topic_0221482440_p85905500385"></a><a name="zh-cn_topic_0221482440_p85905500385"></a>项目描述信息。</p>
</td>
</tr>
<tr id="zh-cn_topic_0221482440_row115832505384"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="zh-cn_topic_0221482440_p13590105013380"><a name="zh-cn_topic_0221482440_p13590105013380"></a><a name="zh-cn_topic_0221482440_p13590105013380"></a><a href="#zh-cn_topic_0221482440_response_Rs63ProjectsArritemLinks">links</a></p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="zh-cn_topic_0221482440_p11591205053819"><a name="zh-cn_topic_0221482440_p11591205053819"></a><a name="zh-cn_topic_0221482440_p11591205053819"></a>Object</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="zh-cn_topic_0221482440_p259215073819"><a name="zh-cn_topic_0221482440_p259215073819"></a><a name="zh-cn_topic_0221482440_p259215073819"></a>项目的资源链接。</p>
</td>
</tr>
<tr id="zh-cn_topic_0221482440_row95841150133819"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="zh-cn_topic_0221482440_p259345053819"><a name="zh-cn_topic_0221482440_p259345053819"></a><a name="zh-cn_topic_0221482440_p259345053819"></a>enabled</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="zh-cn_topic_0221482440_p1859335083813"><a name="zh-cn_topic_0221482440_p1859335083813"></a><a name="zh-cn_topic_0221482440_p1859335083813"></a>Boolean</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="zh-cn_topic_0221482440_p35941950123813"><a name="zh-cn_topic_0221482440_p35941950123813"></a><a name="zh-cn_topic_0221482440_p35941950123813"></a>项目是否可用。</p>
</td>
</tr>
<tr id="zh-cn_topic_0221482440_row165845503382"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="zh-cn_topic_0221482440_p95951250183820"><a name="zh-cn_topic_0221482440_p95951250183820"></a><a name="zh-cn_topic_0221482440_p95951250183820"></a>id</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="zh-cn_topic_0221482440_p1559555013820"><a name="zh-cn_topic_0221482440_p1559555013820"></a><a name="zh-cn_topic_0221482440_p1559555013820"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="zh-cn_topic_0221482440_p10596105016386"><a name="zh-cn_topic_0221482440_p10596105016386"></a><a name="zh-cn_topic_0221482440_p10596105016386"></a>项目ID。</p>
</td>
</tr>
<tr id="zh-cn_topic_0221482440_row7584185063820"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="zh-cn_topic_0221482440_p10597165023812"><a name="zh-cn_topic_0221482440_p10597165023812"></a><a name="zh-cn_topic_0221482440_p10597165023812"></a>parent_id</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="zh-cn_topic_0221482440_p1659725011386"><a name="zh-cn_topic_0221482440_p1659725011386"></a><a name="zh-cn_topic_0221482440_p1659725011386"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="zh-cn_topic_0221482440_p18598750173813"><a name="zh-cn_topic_0221482440_p18598750173813"></a><a name="zh-cn_topic_0221482440_p18598750173813"></a>如果查询自己创建的项目，则此处返回所属区域的项目ID。</p>
<p id="zh-cn_topic_0221482440_p3599165016388"><a name="zh-cn_topic_0221482440_p3599165016388"></a><a name="zh-cn_topic_0221482440_p3599165016388"></a>如果查询的是系统内置项目，如cn-north-4，则此处返回帐号ID。</p>
</td>
</tr>
<tr id="zh-cn_topic_0221482440_row19584205003811"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="zh-cn_topic_0221482440_p3599550183813"><a name="zh-cn_topic_0221482440_p3599550183813"></a><a name="zh-cn_topic_0221482440_p3599550183813"></a>domain_id</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="zh-cn_topic_0221482440_p1760016502380"><a name="zh-cn_topic_0221482440_p1760016502380"></a><a name="zh-cn_topic_0221482440_p1760016502380"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="zh-cn_topic_0221482440_p146011450163815"><a name="zh-cn_topic_0221482440_p146011450163815"></a><a name="zh-cn_topic_0221482440_p146011450163815"></a>项目所属帐号ID。</p>
</td>
</tr>
<tr id="zh-cn_topic_0221482440_row16584125017382"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="zh-cn_topic_0221482440_p6601750113811"><a name="zh-cn_topic_0221482440_p6601750113811"></a><a name="zh-cn_topic_0221482440_p6601750113811"></a>name</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="zh-cn_topic_0221482440_p5602550183810"><a name="zh-cn_topic_0221482440_p5602550183810"></a><a name="zh-cn_topic_0221482440_p5602550183810"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="zh-cn_topic_0221482440_p146031050183810"><a name="zh-cn_topic_0221482440_p146031050183810"></a><a name="zh-cn_topic_0221482440_p146031050183810"></a>项目名称。</p>
</td>
</tr>
</tbody>
</table>

**表 5**  projects.links

<a name="zh-cn_topic_0221482440_response_Rs63ProjectsArritemLinks"></a>
<table><thead align="left"><tr id="zh-cn_topic_0221482440_row13603250173814"><th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.1"><p id="zh-cn_topic_0221482440_p1560415509386"><a name="zh-cn_topic_0221482440_p1560415509386"></a><a name="zh-cn_topic_0221482440_p1560415509386"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.2"><p id="zh-cn_topic_0221482440_p1660513507382"><a name="zh-cn_topic_0221482440_p1660513507382"></a><a name="zh-cn_topic_0221482440_p1660513507382"></a>参数类型</p>
</th>
<th class="cellrowborder" valign="top" width="60%" id="mcps1.2.4.1.3"><p id="zh-cn_topic_0221482440_p1660612503387"><a name="zh-cn_topic_0221482440_p1660612503387"></a><a name="zh-cn_topic_0221482440_p1660612503387"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="zh-cn_topic_0221482440_row360310505389"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.1 "><p id="zh-cn_topic_0221482440_p960712508383"><a name="zh-cn_topic_0221482440_p960712508383"></a><a name="zh-cn_topic_0221482440_p960712508383"></a>self</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="zh-cn_topic_0221482440_p5607185018384"><a name="zh-cn_topic_0221482440_p5607185018384"></a><a name="zh-cn_topic_0221482440_p5607185018384"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="60%" headers="mcps1.2.4.1.3 "><p id="zh-cn_topic_0221482440_p160814506387"><a name="zh-cn_topic_0221482440_p160814506387"></a><a name="zh-cn_topic_0221482440_p160814506387"></a>资源链接地址。</p>
</td>
</tr>
</tbody>
</table>

## 请求示例<a name="zh-cn_topic_0221482440_section3609205073812"></a>

```
GET https://iam.myhuaweicloud.com/v3/auth/projects
```

## 响应示例<a name="zh-cn_topic_0221482440_section56111750203812"></a>

**状态码为 200 时:**

请求成功。

```
{
    "projects": [
        {
            "domain_id": "d78cbac186b744899480f25bd02...",
            "is_domain": false,
            "parent_id": "d78cbac186b744899480f25bd022...",
            "name": "af-south-1",
            "description": "",
            "links": {
                "self": "https://iam.myhuaweicloud.com/v3/projects/06f1cbbaf280106b2f14c00313a9d065"
            },
            "id": "06f1cbbaf280106b2f14c00313a9...",
            "enabled": true
        },
        {
            "domain_id": "d78cbac186b744899480f25bd02...",
            "is_domain": false,
            "parent_id": "d78cbac186b744899480f25bd022...",
            "name": "cn-north-4",
            "description": "",
            "links": {
                "self": "https://iam.myhuaweicloud.com/v3/projects/065a7c66da0010992ff7c0031e5a5e7d"
            },
            "id": "065a7c66da0010992ff7c0031e5a5e7d",
            "enabled": true
        }
    ],
    "links": {
        "self": "https://iam.myhuaweicloud.com/v3/auth/projects"
    }
}
```

## 返回值<a name="zh-cn_topic_0221482440_section10632115012389"></a>

<a name="zh-cn_topic_0221482440_table2431"></a>
<table><thead align="left"><tr id="zh-cn_topic_0221482440_row7633175073819"><th class="cellrowborder" valign="top" width="15%" id="mcps1.1.3.1.1"><p id="zh-cn_topic_0221482440_p1663425043813"><a name="zh-cn_topic_0221482440_p1663425043813"></a><a name="zh-cn_topic_0221482440_p1663425043813"></a>返回值</p>
</th>
<th class="cellrowborder" valign="top" width="85%" id="mcps1.1.3.1.2"><p id="zh-cn_topic_0221482440_p14635950163812"><a name="zh-cn_topic_0221482440_p14635950163812"></a><a name="zh-cn_topic_0221482440_p14635950163812"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="zh-cn_topic_0221482440_row363316509383"><td class="cellrowborder" valign="top" width="15%" headers="mcps1.1.3.1.1 "><p id="zh-cn_topic_0221482440_p46351750133820"><a name="zh-cn_topic_0221482440_p46351750133820"></a><a name="zh-cn_topic_0221482440_p46351750133820"></a>200</p>
</td>
<td class="cellrowborder" valign="top" width="85%" headers="mcps1.1.3.1.2 "><p id="zh-cn_topic_0221482440_p10636145093817"><a name="zh-cn_topic_0221482440_p10636145093817"></a><a name="zh-cn_topic_0221482440_p10636145093817"></a>请求成功。</p>
</td>
</tr>
<tr id="zh-cn_topic_0221482440_row563375043814"><td class="cellrowborder" valign="top" width="15%" headers="mcps1.1.3.1.1 "><p id="zh-cn_topic_0221482440_p9637175013383"><a name="zh-cn_topic_0221482440_p9637175013383"></a><a name="zh-cn_topic_0221482440_p9637175013383"></a>400</p>
</td>
<td class="cellrowborder" valign="top" width="85%" headers="mcps1.1.3.1.2 "><p id="zh-cn_topic_0221482440_p1963755012384"><a name="zh-cn_topic_0221482440_p1963755012384"></a><a name="zh-cn_topic_0221482440_p1963755012384"></a>参数无效。</p>
</td>
</tr>
<tr id="zh-cn_topic_0221482440_row126331950133818"><td class="cellrowborder" valign="top" width="15%" headers="mcps1.1.3.1.1 "><p id="zh-cn_topic_0221482440_p2638155018387"><a name="zh-cn_topic_0221482440_p2638155018387"></a><a name="zh-cn_topic_0221482440_p2638155018387"></a>401</p>
</td>
<td class="cellrowborder" valign="top" width="85%" headers="mcps1.1.3.1.2 "><p id="zh-cn_topic_0221482440_p363918508385"><a name="zh-cn_topic_0221482440_p363918508385"></a><a name="zh-cn_topic_0221482440_p363918508385"></a>认证失败。</p>
</td>
</tr>
<tr id="zh-cn_topic_0221482440_row14633105013385"><td class="cellrowborder" valign="top" width="15%" headers="mcps1.1.3.1.1 "><p id="zh-cn_topic_0221482440_p19640450143815"><a name="zh-cn_topic_0221482440_p19640450143815"></a><a name="zh-cn_topic_0221482440_p19640450143815"></a>403</p>
</td>
<td class="cellrowborder" valign="top" width="85%" headers="mcps1.1.3.1.2 "><p id="zh-cn_topic_0221482440_p0640950193819"><a name="zh-cn_topic_0221482440_p0640950193819"></a><a name="zh-cn_topic_0221482440_p0640950193819"></a>没有操作权限。</p>
</td>
</tr>
<tr id="zh-cn_topic_0221482440_row12633115073813"><td class="cellrowborder" valign="top" width="15%" headers="mcps1.1.3.1.1 "><p id="zh-cn_topic_0221482440_p15641115053810"><a name="zh-cn_topic_0221482440_p15641115053810"></a><a name="zh-cn_topic_0221482440_p15641115053810"></a>404</p>
</td>
<td class="cellrowborder" valign="top" width="85%" headers="mcps1.1.3.1.2 "><p id="zh-cn_topic_0221482440_p166421150203816"><a name="zh-cn_topic_0221482440_p166421150203816"></a><a name="zh-cn_topic_0221482440_p166421150203816"></a>未找到相应的资源。</p>
</td>
</tr>
<tr id="zh-cn_topic_0221482440_row8633205063816"><td class="cellrowborder" valign="top" width="15%" headers="mcps1.1.3.1.1 "><p id="zh-cn_topic_0221482440_p1464205015382"><a name="zh-cn_topic_0221482440_p1464205015382"></a><a name="zh-cn_topic_0221482440_p1464205015382"></a>405</p>
</td>
<td class="cellrowborder" valign="top" width="85%" headers="mcps1.1.3.1.2 "><p id="zh-cn_topic_0221482440_p8643450133813"><a name="zh-cn_topic_0221482440_p8643450133813"></a><a name="zh-cn_topic_0221482440_p8643450133813"></a>不允许的方法。</p>
</td>
</tr>
<tr id="zh-cn_topic_0221482440_row146331650113818"><td class="cellrowborder" valign="top" width="15%" headers="mcps1.1.3.1.1 "><p id="zh-cn_topic_0221482440_p1364455012387"><a name="zh-cn_topic_0221482440_p1364455012387"></a><a name="zh-cn_topic_0221482440_p1364455012387"></a>413</p>
</td>
<td class="cellrowborder" valign="top" width="85%" headers="mcps1.1.3.1.2 "><p id="zh-cn_topic_0221482440_p1064518508387"><a name="zh-cn_topic_0221482440_p1064518508387"></a><a name="zh-cn_topic_0221482440_p1064518508387"></a>请求体过大。</p>
</td>
</tr>
<tr id="zh-cn_topic_0221482440_row763335017389"><td class="cellrowborder" valign="top" width="15%" headers="mcps1.1.3.1.1 "><p id="zh-cn_topic_0221482440_p7645135053812"><a name="zh-cn_topic_0221482440_p7645135053812"></a><a name="zh-cn_topic_0221482440_p7645135053812"></a>500</p>
</td>
<td class="cellrowborder" valign="top" width="85%" headers="mcps1.1.3.1.2 "><p id="zh-cn_topic_0221482440_p126461505387"><a name="zh-cn_topic_0221482440_p126461505387"></a><a name="zh-cn_topic_0221482440_p126461505387"></a>内部服务错误。</p>
</td>
</tr>
<tr id="zh-cn_topic_0221482440_row2633205020386"><td class="cellrowborder" valign="top" width="15%" headers="mcps1.1.3.1.1 "><p id="zh-cn_topic_0221482440_p364755013382"><a name="zh-cn_topic_0221482440_p364755013382"></a><a name="zh-cn_topic_0221482440_p364755013382"></a>503</p>
</td>
<td class="cellrowborder" valign="top" width="85%" headers="mcps1.1.3.1.2 "><p id="zh-cn_topic_0221482440_p7647195010385"><a name="zh-cn_topic_0221482440_p7647195010385"></a><a name="zh-cn_topic_0221482440_p7647195010385"></a>服务不可用。</p>
</td>
</tr>
</tbody>
</table>

## 错误码<a name="zh-cn_topic_0221482440_section86482508383"></a>

无

