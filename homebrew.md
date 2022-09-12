// 安装 brew 根据提示操作即可

/bin/zsh -c "$(curl -fsSL https://gitee.com/cunkai/HomebrewCN/raw/master/Homebrew.sh)"

//添加旧的 PHP 仓库：

brew tap shivammathur/php

//安装完成后，再次搜索

brew search php

//安装切换版本
brew install brew-php-switcher

//安装好后，我现在是 7.1 我要切换到 7.3

brew-php-switcher 7.3
