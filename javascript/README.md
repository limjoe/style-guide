# Sensoro JavaScript 代码规范

所有项目使用 JSHint 和 JSCS 对 JavaScript 进行本地校验，其中 JSHint 偏语法校验，JSCS 偏代码风格校验。 `.jscsrc` 和 `.jshintrc` 文件应该分别放到相应的项目根目录中。

## Vim 配置

	Bundle 'scrooloose/syntastic'
	let g:syntastic_check_on_open=1
	let g:syntastic_javascript_checkers = ['jshint', 'jscs']
