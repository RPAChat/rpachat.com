# The next generation of business messaging

Expanding your messaging strategy just got simpler. RPAChat integrates 5-10+ different chat apps including WhatsApp、WeChat etc.-- you can communicate with your customers on whichever channel they love most.

Build deeper customer relationships at scale with a messaging platform based on trust,quality and choice -- RPAChat, in just 6 lines of code!

Powerful chat apps API that enables you to send, receive and track chat apps effortlessly

## Omnichannel messaging on a single, scalable platform

Support any Chat App in one platform.

Merge all your customer's favourite chat apps into a single, easy-to-use platform.

Powerful Universal API that enables you to send, receive, and track chat app messages effortlessly.

Reach customers on their favorite channels from a single platform

### WhatsApp

### WeChat

### WeCom

### Line (On the way)

## XXXXXXXX

### Rich Media

Enrich your messages with images, audio, video, and files

### Group Management

You have full control of the Chat App (WhatsApp、WeChat、WeCom) Group API that lets you create a group, add/remove a participant, and send/receive a message.

## Developer-friendly APIs for any scale

### Feature1

### Feature2

### Stable API

Multi-device WhatsApp/WeChat/WeCom no longer needs a phone connection, so RPAChat provides better uptime compare to the past.

## Open Source Protocol

By developers, for developers

Build on top of opensource project

We have spent the last 6 years helping over 10,000 developers just like yourself, create their successful business.

Community is a wonderful thing. Connect with ours to discover best practices, untapped solutions, helpful docs, guides, events, blogs, and more. Learn, build, and share with like-minded thinkers.

## RPAChat-based messaging Platform trusted by enterprises

LOGO 墙（放英文公司）

## The all-in-one RPA chat solution

turn every conversation into a conversion with a myriad of channels and tools to help you sell, support and reach customers better.

## Get Started

It takes 3 steps to get started to use RPAChat

1. SET ENV
Set the environment variable WECHATY_PUPPET to change different Chat App，like WhatsApp、WeChat、WeCom

2. Pair Phone
Pair phone by scanning a QR code to connect to RPAChat

3. Sending & Receiving Message
After login the, you can use event driven SDK to send and receive the message

## Just 6 lines of JavaScript, all done

```ts
import { WechatyBuilder } from 'wechaty'

const wechaty = WechatyBuilder.build() // get a Wechaty instance
wechaty
  .on('scan', (qrcode, status) => console.log(`Scan QR Code to login: ${status}\nhttps://wechaty.js.org/qrcode/${encodeURIComponent(qrcode)}`))
  .on('login',            user => console.log(`User ${user} logged in`))
  .on('message',       message => console.log(`Message: ${message}`))
wechaty.start()
```

__We cannot wait to see what you build__
footer
