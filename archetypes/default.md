+++
date = '{{ .Date }}'
draft = true
title = '{{ replace .File.ContentBaseName "-" " " | title }}'
[Params]
    [author]
        id = ''
        name = ''
+++
