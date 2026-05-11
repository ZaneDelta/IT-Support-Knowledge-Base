# Windows Update Troubleshooting

## Symptoms
- Windows update stuck
- Update failed repeatedly
- System unable to download updates

## Troubleshooting Steps

### 1. Restart Windows Update Service
Open Command Prompt as Administrator:

```cmd
net stop wuauserv
net start wuauserv