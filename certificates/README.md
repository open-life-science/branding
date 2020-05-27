# Certificates

## Generation for awardees

Certificates for awardees can be automatically generated using the [NextGenerator](https://gitlab.com/Moini/nextgenerator) extension for Inkscape:

1. Install the extension by following [Inkscape instructions](https://inkscape.org/fr/gallery/=extension/)
2. Create a CSV
    - 2 columns (name, project)
    - 1st line being `name,project`
    - one line per awardee
3. Open the SVG file with the certificate
4. Run the NextGenerator extension
    - Export in PDF
    - File name pattern `%VAR_name%`
5. Add signature