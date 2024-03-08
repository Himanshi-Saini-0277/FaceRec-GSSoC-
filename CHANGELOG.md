## [0.0.1] - 2024-03-08 - 2:30

### Added
- Implemented all test cases in `test_face_cycle`
- Implemented mock test cases for `test_face_cycle` to work on online runners

## [0.1.0] - 2024-03-08 - 17:10

### Added
- Updated `create_new_faceEntry` function in [`route.py`](route/route.py) to handle multiple images for each employee.
- Updated `test_face_lifecycle` function in [`test_face_cycle.py`](testing/test_face_cycle.py) to handle multiple images for each employee in the test data.

### Changed
- Modified the `Employee` and `UpdateEmployee` models in [`route.py`](route/route.py) to include a list of images instead of a single image.
- Adjusted the mock data and assertions in [`test_face_cycle.py`](testing/test_face_cycle.py) to handle multiple images for each employee.

### Fixed
- Resolved an issue where the `create_new_faceEntry` function in [`route.py`](route/route.py) was not correctly processing multiple images for each employee.