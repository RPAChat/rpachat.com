 +--------------------------+ +--------------------------+
  |                          | |                          |
  |   Wechaty (TypeScript)   | |    Wechaty(Polyglot)     |
  |                          | |  Python, Go, Rust, etc.  |
  +--------------------------+ +--------------------------+

  +-------------------------------------------------------+
  |                 Wechaty Puppet Service                |
  |                          client                       |            TS/Python/Java....
  |                (wechaty-puppet-service )              |
  +-------------------------------------------------------+

+---------------------  wechaty_grpc  ----------------------+

  +-------------------------------------------------------+
  |                 Wechaty Puppet Service                |
  |                          server                       |            TS Only
  |                (wechaty-puppet-service )              |
  +-------------------------------------------------------+

  +-------------------------------------------------------+
  |                   Wechaty Puppet                      |
  |                                                       |
  |                   (wechaty-puppet)                    |
  +-------------------------------------------------------+

  +--------------------------+ +--------------------------+
  |      Pad Protocol        | |      Web Protocol        |
  |                          | |                          |
  | wechaty-puppet-padlocal  | |  (wechaty-puppet-wechat) |
  +--------------------------+ +--------------------------+
  +--------------------------+ +--------------------------+
  |     Friday Protocol      | |       Mac Protocol       |
  |                          | |                          |
  |  (wechaty-puppet-frida)  | |   (wechaty-puppet-mac)   |
  +--------------------------+ +--------------------------+

  1. WECHATY_TOKEN (wechaty) -- server
  2. WECHATY_PUPPET_SERVICE_TOKEN (wechaty-puppet-service)  -- client, 用哪个 token 去连服务器

- WECHATY_TOKEN = wechaty-puppet-service server token
- WECHATY_PUPPET_SERVICE_TOKEN = wechaty-puppet-service client token

  2. WECHATY_PUPPET_PADLOCAL_TOKEN (wechaty-puppet-padlocal)
    - 如果在 client 端，就是图1（彩色的）
    - 如果在 server 端，就是图2（本文档里的）
  3. WECHATY_PUPPET_WECHAT_TOKEN  (wechaty-puppet-wechat)
  

  图2：所有的用户都是使用 WECHATY_PUPPET_SERVICE_TOKEN 做认证
  图1：用 WECHATY_PUPPET_PADLOCAL_TOKEN/WECHATY_PUPPET_WECHAT_TOKEN 。。。