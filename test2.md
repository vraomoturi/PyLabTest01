datestr
ignore:
  # False positive, see https://github.com/anchore/grype/issues/558
  - vulnerability: CVE-2015-5237
  fix-state: unknown
  package:
    name: google.golang.org/protobuf
    version: v1.26.0
    type: go-module
    location: "/manager"
