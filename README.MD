## @yaatp/format-report-portal
This package is formatter for EPAM report portal

### install
`npm install @yaatp/format-report-portal`

### configuration

add formatter to config.js
```javascript
module.exports = {
    default: {
        format: [
            '@yaatp/format-report-portal'
        ],
        formatOptions: {
            rpConfig: {
                token: 'your token',
                endpoint: 'https://your-rp-instance/api/v1',
                description: 'Description',
                tags: ['Tag'],
                project: 'your project',
                launch: 'your launch name'
            },
        }
    }
}
```