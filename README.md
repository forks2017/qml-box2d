+ Add two commands below to project setting in qt creator:

nmake install
qmlplugindump -notrelocatable Box2D 2.0 %{CurrentProject:QT_HOST_BINS}/../qml/Box2D > %{CurrentProject:QT_HOST_BINS}/../qml/Box2D/plugin.qmltypes