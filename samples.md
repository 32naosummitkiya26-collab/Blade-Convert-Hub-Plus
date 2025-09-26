# Importable samples

I was actually planning to release it once I had completely converted 50 themes by different authors. I thought that if I could get that far, I would be able to absorb the quirks of various writing styles. However, I'm only developing this as a hobby, and I don't use the templates converted with BCH+ in actual development, so I can't judge whether or not it will be useful to the public.
I wanted to hear whether BCH+ is an app that everyone will support, so I decided to release it even though it's incomplete.

- Append (5 files)
- MS-Copilot (4 files)
- ChatGTP (5 files)
- Startbootstrap-personal (4 files)
- Constra-bootstrap-vsc (17 files)
- Star-admin2 (9 files)
- Light-bootstrap-dashboard (8 files)
- Bootstrap-dashboard-2.1.1-vsc (6 files)
- Material-dashboard (11 files)
- CoolAdmin-master (24 files)

I also downloaded about 15 other random themes (200 files total), and will test them one by one and add the ones that work well.

# Edited original

Basically, I respect the original source code and have made as few changes as possible. The only changes I have made are the following five points.

### 1. Replace with '_'
'-' used in file names is replaced with '_'. If a '.' is used in a folder name, the converted file name will be without the '.'

　　Bootstrap-dashboard-2.1.1-vsc  ->  bootstrap_dashboard_211_vsc_1.blade.php

### 2. Indentation

Adjusted the indentation of the conversion results.

### 3. Combine into one line

Combine external links that were split into two lines into one line.

### 4. Delete comments and blank lines

Comments, blank lines (line breaks), and conditional comments that depend on IE are deleted.
  
### 5. @yield('external_link')
  
If there are external links, BCH+ add them regardless of whether they contain differences or not. You probably won't use the original as is, so it's better to have them for expandability.
