
Yaml yaml = new Yaml();
InputStream inputStream = YamlReader.class.getClassLoader().getResourceAsStream("config.yml");
Map<String, Object> yamlData = yaml.load(inputStream);
