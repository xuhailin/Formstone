{"template":"component.html","title":"Equalize","demo":"<style>\r\n\t.equalize_target { background: #eceff1; margin-bottom: 10px; padding: 15px; }\r\n\t.equalize_target p { margin: 0; }\r\n\t.equalize_child { background: #CFD8DC; }\r\n\t.equalize_group { padding-bottom: 15px; }\r\n\t.equalize_two { font-size: 12px; font-style: italic; }\r\n\t.equalize img { max-width: 100%; }\r\n</style>\r\n\r\n<h4>Basic</h4>\r\n<div class=\"fs-row equalize js-equalize\">\r\n\t<div class=\"fs-cell fs-all-third equalize_target\">\r\n\t\t<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec id elit non mi porta gravida at eget metus. Aenean lacinia bibendum nulla sed consectetur. Donec id elit non mi porta gravida at eget metus.</p>\r\n\t</div>\r\n\t<div class=\"fs-cell fs-all-third equalize_target\">\r\n\t\t<p>Vivamus sagittis lacus vel augue laoreet rutrum faucibus dolor auctor. Aenean eu leo quam. Pellentesque ornare sem lacinia quam venenatis vestibulum. Cras mattis consectetur purus sit amet fermentum.</p>\r\n\t</div>\r\n\t<div class=\"fs-cell fs-all-third equalize_target\">\r\n\t\t<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam quis risus eget urna mollis ornare vel eu leo. Fusce dapibus, tellus ac cursus commodo, tortor mauris condimentum nibh, ut fermentum massa justo sit amet risus. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus.</p>\r\n\t</div>\r\n</div>\r\n\r\n<h4>Min Width</h4>\r\n<div class=\"fs-row equalize js-equalize\" data-equalize-options='{\"minWidth\":\"740px\"}'>\r\n\t<div class=\"fs-cell fs-sm-full fs-md-third fs-lg-third equalize_target\">\r\n\t\t<p>Vivamus sagittis lacus vel augue laoreet rutrum faucibus dolor auctor. Aenean eu leo quam. Pellentesque ornare sem lacinia quam venenatis vestibulum. Cras mattis consectetur purus sit amet fermentum.</p>\r\n\t</div>\r\n\t<div class=\"fs-cell fs-sm-full fs-md-third fs-lg-third equalize_target\">\r\n\t\t<p>Vivamus sagittis lacus vel augue laoreet rutrum faucibus dolor auctor. Aenean eu leo quam. Pellentesque ornare sem lacinia quam venenatis vestibulum. Cras mattis consectetur purus sit amet fermentum.</p>\r\n\t</div>\r\n\t<div class=\"fs-cell fs-sm-full fs-md-third fs-lg-third equalize_target\">\r\n\t\t<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam quis risus eget urna mollis ornare vel eu leo. Fusce dapibus, tellus ac cursus commodo, tortor mauris condimentum nibh, ut fermentum massa justo sit amet risus. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus.</p>\r\n\t</div>\r\n</div>\r\n\r\n<h4>Children</h4>\r\n<div class=\"fs-row equalize js-equalize\" data-equalize-options='{\"target\":\".equalize_child\"}'>\r\n\t<div class=\"fs-cell fs-all-third equalize_target\">\r\n\t\t<p class=\"equalize_child\">Vivamus sagittis lacus vel augue laoreet rutrum faucibus dolor auctor. Aenean eu leo quam. Pellentesque ornare sem lacinia quam venenatis vestibulum. Cras mattis consectetur purus sit amet fermentum.</p>\r\n\t</div>\r\n\t<div class=\"fs-cell fs-all-third equalize_target\">\r\n\t\t<p class=\"equalize_child\">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam quis risus eget urna mollis ornare vel eu leo. Fusce dapibus, tellus ac cursus commodo, tortor mauris condimentum nibh, ut fermentum massa justo sit amet risus. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus.</p>\r\n\t</div>\r\n\t<div class=\"fs-cell fs-all-third equalize_target\">\r\n\t\t<p class=\"equalize_child\">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec id elit non mi porta gravida at eget metus. Aenean lacinia bibendum nulla sed consectetur. Donec id elit non mi porta gravida at eget metus.</p>\r\n\t</div>\r\n</div>\r\n\r\n<h4>Groups</h4>\r\n<div class=\"fs-row equalize js-equalize\" data-equalize-options='{\"target\":[\".equalize_one\",\".equalize_two\"]}'>\r\n\t<div class=\"fs-cell fs-all-third equalize_target\">\r\n\t\t<p class=\"equalize_one equalize_group\">Vivamus sagittis lacus vel augue laoreet rutrum faucibus dolor auctor. Aenean eu leo quam. Pellentesque ornare sem lacinia quam venenatis vestibulum. Cras mattis consectetur purus sit amet fermentum.</p>\r\n\t\t<p class=\"equalize_two\">Donec ullamcorper nulla non metus auctor fringilla.</p>\r\n\t</div>\r\n\t<div class=\"fs-cell fs-all-third equalize_target\">\r\n\t\t<p class=\"equalize_one equalize_group\">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam quis risus eget urna mollis ornare vel eu leo. Fusce dapibus, tellus ac cursus commodo, tortor mauris condimentum nibh, ut fermentum massa justo sit amet risus. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus.</p>\r\n\t\t<p class=\"equalize_two\">Nulla vitae elit libero, a pharetra augue.</p>\r\n\t</div>\r\n\t<div class=\"fs-cell fs-all-third equalize_target\">\r\n\t\t<p class=\"equalize_one equalize_group\">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec id elit non mi porta gravida at eget metus. Aenean lacinia bibendum nulla sed consectetur. Donec id elit non mi porta gravida at eget metus.</p>\r\n\t\t<p class=\"equalize_two\">Nullam id dolor id nibh ultricies vehicula ut id elit.</p>\r\n\t</div>\r\n</div>\r\n\r\n<h4>Images</h4>\r\n<div class=\"fs-row equalize js-equalize\">\r\n\t<div class=\"fs-cell fs-all-third equalize_target\">\r\n\t\t<img src=\"//spacehold.it/400x300/1.jpg\" alt=\"\">\r\n\t</div>\r\n\t<div class=\"fs-cell fs-all-third equalize_target\">\r\n\t\t<img src=\"//spacehold.it/400x200/2.jpg\" alt=\"\">\r\n\t</div>\r\n\t<div class=\"fs-cell fs-all-third equalize_target\">\r\n\t\t<img src=\"//spacehold.it/400x400/3.jpg\" alt=\"\">\r\n\t</div>\r\n</div>","asset_root":"../"}

 #Equalize Demo