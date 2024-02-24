# Evolution of Web Standards: Navigating the Transition from Browser-Specific to W3C Guidelines

- In the early days of the World Wide Web, there were two prominent web browsers, Netscape Navigator and Microsoft Internet Explorer, each with its own way of interpreting and displaying web pages. However, there was a lack of standardized rules for how web pages should be written and displayed.

As a result, when the World Wide Web Consortium (W3C) established web standards to bring uniformity to web development, there was a challenge in implementing these standards. If browsers immediately started using the new standards, it could potentially break the majority of existing websites that were designed based on the earlier, non-standardized practices.

To address this compatibility issue, browsers introduced two modes:

Standards Mode (or Strict Mode): This mode was designed to render web pages that adhered to the newly established W3C standards. Websites built with these standards in mind would be displayed as intended in this mode.

Quirks Mode (or Compatibility Mode): This mode aimed to maintain compatibility with older, non-standardized web pages. Websites that were created before the adoption of web standards would be rendered in this mode to prevent them from breaking due to sudden changes in rendering rules.

So, when a user visited a webpage, the browser would determine whether the page followed the new standards or not. If it did, the browser would render the page in Standards Mode; otherwise, it would use Quirks Mode. This approach allowed for a smoother transition to standardized web development practices without causing widespread issues for existing websites.
