# upgraded 디렉토리 구조 설명

```
upgraded/
├── MANIFEST.in
├── README.rst
├── README_ko.md
├── distribute-0.6.10.tar.gz
├── distribute_setup.py
├── docs/
│   ├── Makefile
│   ├── build/
│   │   ├── doctrees/
│   │   │   ├── changelog.doctree
│   │   │   ├── environment.pickle
│   │   │   ├── example_usage.doctree
│   │   │   ├── getting_started.doctree
│   │   │   ├── index.doctree
│   │   │   └── other_uses.doctree
│   │   └── html/
│   │       ├── .buildinfo
│   │       ├── _sources/
│   │       │   ├── changelog.txt
│   │       │   ├── example_usage.txt
│   │       │   ├── getting_started.txt
│   │       │   ├── index.txt
│   │       │   └── other_uses.txt
│   │       ├── _static/
│   │       │   ├── basic.css
│   │       │   ├── default.css
│   │       │   ├── doctools.js
│   │       │   ├── file.png
│   │       │   ├── jquery.js
│   │       │   ├── minus.png
│   │       │   ├── plus.png
│   │       │   ├── pygments.css
│   │       │   ├── searchtools.js
│   │       │   ├── sidebar.js
│   │       │   └── underscore.js
│   │       ├── changelog.html
│   │       ├── example_usage.html
│   │       ├── genindex.html
│   │       ├── getting_started.html
│   │       ├── index.html
│   │       ├── objects.inv
│   │       ├── other_uses.html
│   │       ├── search.html
│   │       └── searchindex.js
│   └── source/
│       ├── _static/
│       │   └── default.css
│       ├── changelog.rst
│       ├── conf.py
│       ├── example_usage.rst
│       ├── getting_started.rst
│       ├── index.rst
│       └── other_uses.rst
├── guachi/
│   ├── __init__.py
│   ├── config.py
│   ├── database.py
│   └── tests/
│       ├── test_configmapper.py
│       ├── test_configurations.py
│       ├── test_database.py
│       └── test_integration.py
├── guachi.egg-info/
│   ├── PKG-INFO
│   ├── SOURCES.txt
│   ├── dependency_links.txt
│   └── top_level.txt
└── setup.py
```

- `docs/` : 문서 관련 파일 및 빌드 결과물
- `guachi/` : 파이썬 패키지 소스 및 테스트 코드
- `guachi.egg-info/` : 패키지 메타데이터
- `setup.py`, `MANIFEST.in` 등 : 패키지 배포 관련 파일
- 기타 README, 압축 파일 등 포함
