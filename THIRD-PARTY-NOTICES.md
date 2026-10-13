# A2Rank — 서드파티 구성요소 고지

A2Rank는 아래 오픈소스를 **고치지 않고 그대로** 포함합니다. 각 구성요소의 저작권은 각 권리자에게 있고, 각자의 라이선스 조건을 따릅니다.

| 구성요소 | 용도 | 라이선스 | 저작권 |
|---|---|---|---|
| .NET 8 런타임·라이브러리, WPF | 실행 환경 | MIT | © .NET Foundation and Contributors, Microsoft |
| SharpPcap 6.3.0 | 패킷 캡처 | MIT | © Tamir Gal, Chris Morgan and others |
| PacketDotNet 1.4.7 | 패킷 해석 | MPL-2.0 | © Chris Morgan and others |
| Microsoft.Data.Sqlite 8.0.10 | 로컬 기록 저장 | MIT | © Microsoft Corporation |
| SQLitePCLRaw 2.1.6 | SQLite 연결 | Apache-2.0 | © 2014-2023 SourceGear, LLC (Eric Sink) |
| SQLite | 데이터베이스 엔진 | 퍼블릭 도메인 | SQLite 개발자 |
| Velopack 1.2.161 | 설치와 자동 업데이트 | MIT | © Velopack Ltd, Caelan Sayler, Kevin Bost |

패킷 캡처는 사용자가 따로 설치하는 **Npcap**(https://npcap.com)을 사용합니다. Npcap은 A2Rank에 포함되어 있지 않고, 자체 라이선스를 따릅니다.

## 라이선스 전문
- MIT: https://opensource.org/license/mit
- Apache License 2.0: https://www.apache.org/licenses/LICENSE-2.0
- Mozilla Public License 2.0: https://www.mozilla.org/MPL/2.0/ (PacketDotNet의 소스: https://github.com/dotpcap/packetnet — A2Rank는 이를 수정하지 않았습니다)

### MIT 라이선스 (위 MIT 구성요소 공통 조건)
Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

---
A2Rank 자체의 사용 조건은 [이용 안내](TERMS.md)를 따릅니다.
