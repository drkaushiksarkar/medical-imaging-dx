# Medical Imaging Dx

Medical imaging diagnostics platform for classification and segmentation of radiological images using deep learning.

## Architecture

```
medical-imaging-dx/
  src/           # Core modules
  tests/         # Unit and integration tests
  config/        # Configuration files
  docs/          # Documentation
```

## Modules

- **image_loader**: Core image loader functionality
- **preprocessor**: Core preprocessor functionality
- **classifier**: Core classifier functionality
- **segmenter**: Core segmenter functionality
- **report_generator**: Core report generator functionality

## Quick Start

```bash
pip install -r requirements.txt
python -m medical_imaging_dx.main
```

## Testing

```bash
pytest tests/ -v
```

## License

MIT License - see LICENSE for details.
