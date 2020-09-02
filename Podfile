source 'https://github.com/CocoaPods/Specs'


def thridparty
    pod 'SSZipArchive', :git => 'https://github.com/ddaddy/ZipArchive.git', :branch => 'master'
end

target 'XlsxReaderWriter' do
    platform :ios, '9.0'
    thridparty
    use_frameworks!
end

target 'XlsxReaderWriter-iOS' do
    platform :ios, '9.0'
    thridparty
    use_frameworks!
end

target 'XlsxReaderWriter-Mac' do
    platform :macos, '10.9'
    thridparty
    use_frameworks!
end

target 'XlsxReaderWriter-WatchOS' do
    platform :watchos, '3.0'
    thridparty
    use_frameworks!
end

target 'XlsxReaderWriterTests' do
    platform :ios, '9.0'
    thridparty
	use_frameworks!
end
