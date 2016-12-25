# Facebook Bot Java Library

The current work is a cooperation between [Marco Scheid](https://br.linkedin.com/in/marco-a-scheid) and [Igor Volanski](https://br.linkedin.com/in/igor-volanski-a2813121/en), from Brazil.

Java library to create bots using Facebook Bots API

## Getting Started

  1. Download!

   Get the jar from [here](https://github.com/marcoscheid/Facebook-Bot-API/releases), and add it to your project.

  2. Extend!

   Create a new class, extending `br.com.facebook.bot.api.principal.FacebookBot`

  3. Expand!   
  
  You must provide an implementation to Facebook API's abstract methods. You will need to design a treatment to all incoming interactions via [Facebook Webhooks](https://developers.facebook.com/docs/messenger-platform/webhook-reference), and provide your Facebook Token.
  
  Well, this explanation may not be enough. For a more complete explanation, visite our [HOW-TO].  

## Facebook Developers Messenger Platform Documentation
This library uses [Facebook Developers Messenger Platform Documentation](https://developers.facebook.com/docs/messenger-platform), you can find more information following the link.
Friend's tip: you will probably want to pay special attention to [Webhook Reference](https://developers.facebook.com/docs/messenger-platform/webhook-reference) and [Send API Reference](https://developers.facebook.com/docs/messenger-platform/send-api-reference).

## Questions or Suggestions
Feel free to create issues [here](https://github.com/marcoscheid/Facebook-Bot-API/issues) as you need or email me: marcoaurelioscheid@gmail.com

## License 
License

Copyright (c) 2016 Marco A. Scheid

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
