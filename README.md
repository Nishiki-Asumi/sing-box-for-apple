# sing-box-for-apple

Experimental iOS/macOS/tvOS client for sing-box, the universal proxy platform.

>[!CAUTION]
> I initially forked this to provide an open and transparent build, as the official package on the App Store has been long outdated, and no IPA or build scripts have been provided through any other *public* channels. 
> 
> However, due to Apple's restrictions, even if you can successfully build the IPA, it cannot be installed and used on non-jailbroken devices (free personal developer accounts cannot obtain Network Extensions entitlement, and even paid accounts require Apple's approval. Very Few leaked enterprise certificates may have this entitlement, but they are not guaranteed to work and may be revoked at any time).
> 
> Therefore, this project is no longer practical. My recommendation is that if you do not have the necessary conditions, do not continue to waste your time -- I have wasted hours on this and I do not want others to go through the same experience. But if you still want to try, you can check the build scripts in `.github/workflows/` for reference.
>
> So Apple, fuck you.

## Documentation

[SFI](https://sing-box.sagernet.org/installation/clients/sfi/) | [SFM](https://sing-box.sagernet.org/installation/clients/sfm/)

## License

```
Copyright (C) 2022 by nekohasekai <contact-sagernet@sekai.icu>

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program. If not, see <http://www.gnu.org/licenses/>.
```