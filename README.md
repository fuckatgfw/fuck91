# 91porn 视频查询和播放接口

## 视频列表查询

**地址**: `https://www.lulutang.com/api/video_list_query`

**请求方式**: `GET`

**参数**:

- `title` 名称（支持模糊查询）
- `vid` 视频 ID
- `view_key` 官网视频 key
- `add_time` 添加日期
- `heat` 热度
- `favorites` 收藏
- `comments` 评论数

## 获取 Token

**地址**: `https://www.lulutang.com/api/get_token`

**请求方式**: `GET`

**参数**:

- `vid` 视频 ID
- `key` 密钥（发邮件到 `fuckatgfw@protonmail.com` 获取）

## 视频播放（轻点薅，没多少流量）

**地址**: `https://play.lulutang.com/api/video_view`

**请求方式**: `GET`

**参数**:

- `vid` 视频 ID
- `token` 通过 token 获取地址获取到的值