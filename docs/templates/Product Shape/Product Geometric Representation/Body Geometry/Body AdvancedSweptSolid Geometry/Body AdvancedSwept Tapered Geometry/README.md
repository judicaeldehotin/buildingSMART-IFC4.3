Body AdvancedSwept Tapered Geometry
===================================



```
concept {
    IfcElement:Representation -> IfcProductDefinitionShape
    IfcProductDefinitionShape:Representations -> IfcShapeRepresentation
    IfcShapeRepresentation:ContextOfItems -> IfcGeometricRepresentationContext
    IfcShapeRepresentation:RepresentationIdentifier -> IfcLabel
    IfcShapeRepresentation:RepresentationType -> IfcLabel
    IfcShapeRepresentation:Items -> IfcExtrudedAreaSolidTapered
    IfcShapeRepresentation:Items -> IfcRevolvedAreaSolidTapered
    IfcShapeRepresentation:RepresentationIdentifier[binding="Identifier"]
    IfcShapeRepresentation:RepresentationType[binding="Type"]
    IfcShapeRepresentation:Items[binding="Items"]
}
```
