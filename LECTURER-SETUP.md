# Lecturer Repository Setup

## Recommended Settings

### Protect the `main` Branch

Enable a branch protection ruleset for `main`:

- require a Pull Request before merging;
- prevent force pushes;
- prevent branch deletion;
- require conversation resolution; and
- restrict direct updates where appropriate.

### Student Access

The recommended workflow is **fork and Pull Request**. Students do not need direct write access to the repository.

### Pull Request Review

Confirm:

- the student used the correct Section;
- the folder name contains the correct matric number;
- only the student's folder was changed;
- the exercise README is complete;
- evidence is accessible;
- no secret or private data was uploaded; and
- sources and AI assistance are declared.

### Suggested Labels

- `section-01`
- `section-02`
- `section-03`
- `section-04`
- `exercise-01`
- `needs-changes`
- `reviewed`
- `approved`

## Future Extensions

Consider adding GitHub Actions later to check folder names, required README files, file sizes and accidental credential uploads.
